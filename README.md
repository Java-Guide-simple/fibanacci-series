package interviewjavaprogram;

// Fibonacci series ----  Next number is sum of previous two numbers .
// 0 , 1 , 1 , 2 , 3, 5 , 8, 13, 21 , 34 , 55 ....................

// 0,1, 1 ,2 ,3 ,5,...

public class Fibonacci {

	public static void main(String[] args) {

		int number1 = 0, number2 = 1, number3;

		// PRINTING first 10 digits of fibonacci series
		
		System.out.print("Fibonaci Series is :  " + number1 + " , " + number2 );

		for (int i = 0; i < 8; i++) {

			number3 = number1 + number2;
			System.out.print( " , " +number3 );

			number1 = number2;
			number2 = number3;
			
		}

	}

}
