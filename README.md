import java.util.Scanner;

public class Class {
	
	
	
	
	public static Scanner scan = new Scanner(System.in);
	

	
	int classc = scan.nextInt();
	int casec = 0;  

	
	public static void main(String[] args) {
			 
		
		System.out.println("Please type in a number from 1-10"
				+ ", 1 = math"
				+ ""
				+ ", 2 = english"
				+ ""
				+ ", 3 = french"
				+ ""
				+ ", 4 = science"
				+ ""
				+ ", 5 = religion"
				+ ""
				+ ", 6 = gym"
				+ ""
				+ ", 7 = music"
				+ ""
				+ ", 8 = CP3"
				+ ""
				+ ", 9 = history"
				+ ""
				+ ", 10 = speech"
				+ ""
				+ ", 11 = homeroom"); 
		
		int classc = scan.nextInt();
		int casec = 0; 

		
		//if statement 
		if (classc == 1){	
			casec = casec + 1; 
		
		}else if (classc == 2){
			casec = casec + 2; 
		
		}else if (classc == 3){
			casec = casec + 3;
		
		}else if (classc == 4){
		
			casec = casec + 4; 
		
		}else if (classc == 5){
			casec = casec + 5;
		
		}else if (classc == 6){
			casec = casec + 6;
		
		}else if (classc == 7){
			casec = casec + 7; 
		
		}else if (classc == 8){
			casec = casec + 8;
			
		}else if (classc == 9){
			casec = casec + 9;
			
		}else if (classc == 10){
			casec = casec + 10; 
			
		}else if (classc == 11){
			casec = casec + 11; 
		}
		
	
			//switch 
			switch (casec) {
		
		case 1 : System.out.println("You have math on days: "
				+ "1,2,4,7,8 and all A days");
			break; 
		
		case 2 : System.out.println("You have English on days:"
				+ "1,2,5 and 7 ");
			break;
		case 3 : System.out.println("You have French on days:"
				+ "1,3,5,6,7 and all A days");
			break;
		case 4 : System.out.println("You have Science on days:"
				+ "2,4,5,6 and all A days");
			break; 
		case 5 : System.out.println("You have Religion on days:"
				+ "1,3,4 and 5"); 
			break; 
		case 6 : System.out.println("You have Gym on days:"
				+ "2,3 and 8");
			break; 
		case 7: System.out.println("You have Music on days:"
				+ "2,4,6 and 8");
			break;
		case 8 : System.out.println("You have Computer Programming on days:"
				+ "1,4,7 and all A days");
			break;
		case 9 : System.out.println("You have History on days:"
				+ "3,5,6,7 and 8");
			break; 
		case 10 : System.out.println("You have Speach on days 3 and 7");
			break; 
		case 11 : System.out.println("You have Homeroom on day 1"); 
	
		}//end of switch 


			


}//end of main void
}//end of class
		
