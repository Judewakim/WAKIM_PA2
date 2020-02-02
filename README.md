# WAKIM_PA2
package wakim_p2;
import java.util.Scanner;

public class Wakim_p2 {
	
	private static final Scanner Scanner = null;

//	static int readFromUser(int userWeight, int userHeight) {
//		//ask and scan weight and height 
////		Scanner input = new Scanner( System.in);
////		int userHeight;
////		int userWeight;
//////		int BMIoption;
////		System.out.print("Enter height in inches: \n");
//////		userHeight = input.nextInt();
////		System.out.print("Enter weight in pounds: \n");
////		userWeight = input.nextInt();
////		System.out.print("Enter 1 for pounds/inches or 2 for kilograms/meters: \n");
////		BMIoption = input.nextInt();
//		
//		return (userHeight + userWeight);
//	}
	
//	public static int calculate (int userHeight, int userWeight) {
////		insert numbers in formula 
////		int BMI;
////		if (BMIoption == 1) {
////			int BMI = (userWeight * 703) / (userHeight * userHeight);
////			System.out.print("Your calculated BMI is %d.\n"+ BMI);
////		}
////		
////		else if (BMIoption == 2) {
////			BMI = (userWeight) / (userHeight * userHeight);
////			System.out.print("Your calculated BMI is %d.\n"+ BMI);
////		}
//////		else {
////			System.out.print("Invalid number. Restart\n");
////		}
//		
//		return BMI;
//	}
//	
//	public static int display (int BMI) {
//		 if ( BMI < 18.5 )
//		  {
//		    System.out.println("You are currently underweight");
//		  }
//		  
//		  if ( BMI >= 18.5 && BMI <= 24.9 )
//		  {
//		    System.out.println("You are currently normal");
//		  }
//		  
//		  if ( BMI >= 25 && BMI <=29.9 )
//		  {
//			System.out.println("You are currently overweight");
//		  }
//		  
//		  if ( BMI > 30)
//		  {
//			  System.out.println("You are currently obese");
//		  }
//		  
//          return 0;
//	}
	
	public static void main(String[] args) {
		
		Scanner input = new Scanner( System.in);	
		System.out.print("Enter height in inches: \n");
		double userHeight = input.nextDouble();
		
		System.out.print("Enter weight in pounds: \n");
		double userWeight = input.nextDouble();
		
		double BMI = (userWeight * 703) / (userHeight * userHeight);
		System.out.print("Your calculated BMI is " + BMI);
		        
		if ( BMI < 18.5 )
		  {
		    System.out.println("\nYou are currently underweight");
		  }
		  
		  if ( BMI >= 18.5 && BMI <= 24.9 )
		  {
		    System.out.println("\nYou are currently normal");
		  }
		  
		  if ( BMI >= 25 && BMI <= 29.9 )
		  {
			System.out.println("\nYou are currently overweight");
		  }
		  
		  if ( BMI > 30)
		  {
			  System.out.println("\nYou are currently obese");
		  }
	}

//		initalize varible parameters
//    	int userHeight; 
//		int userWeight;
//      int BMI; 
//		int BMIoption;
//        
      
    
		//function calls
//		 readFromUser(userHeight, userWeight);
//    	 calculate(userHeight, userWeight);
//		 display(BMI);
//		
		//DIDNT RUN AS FUNCTIONS SO IT DEVOLVED INTO THE MAIN BUT AT LEAST RUNS
	
	}
