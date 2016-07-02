import java.util.Scanner;
public class Project3_DaraOlayiwola {

	public static void main(String[] args) {
		
		//create variables for program, including constants 
		
		final int EXPECTED_FREQ_FOR_1 = 30;
		final int EXPECTED_FREQ_FOR_2 = 18;
		final int EXPECTED_FREQ_FOR_3 = 13;
		final int EXPECTED_FREQ_FOR_4 = 10;
		final int EXPECTED_FREQ_FOR_5 = 8;
		final int EXPECTED_FREQ_FOR_6 = 7;
		final int EXPECTED_FREQ_FOR_7 = 6;
		final int EXPECTED_FREQ_FOR_8 = 5;
		final int EXPECTED_FREQ_FOR_9 = 5;
		final int NUM_OF_ELEMENTS = 10;
		
		Scanner input = new Scanner(System.in);
		
		int[] userVals = new int[NUM_OF_ELEMENTS];
		int[] valueCount = new int[9];
		
		int brenfordScore = 0;
		int value = 0;
		int i = 0;
		int k = 0;
		int j = 0;
		//ask user for input 
		
		System.out.println("Welcome to the Benford Fraud Detector!");
		
		System.out.print("Please enter 10 numbers: ");
			for (i = 0; i < NUM_OF_ELEMENTS; ++i) {
				userVals[i] = input.nextInt();
			}
		
		//create and display menu for use to see
		System.out.println("Here are your Brenford scores:");
		System.out.println("Digit     Expected     Actual     Difference");
		System.out.println("============================================");
		}
		}
