# switchcasee
project
package switchcase;
import java.util.Scanner;
public class Switchcase {

	public static void main(String[] args) {
		   Scanner in = new Scanner(System.in);
	      
	        System.out.println("1\t hi");
	        System.out.println("2\t hey");
	        System.out.println("3\t hello");
	       

	        System.out.println("Please enter your choice:");
	        
	      
	        int choice=in.nextInt();
	         
	        
	            switch (choice) {
	            case 1: System.out.println("hi"); 
		                break;
	            case 2: System.out.println("hey");
	                    break;
	            case 3: System.out.println("hello"); 
	                    break;
	            default: System.out.println("Invalid choice");
		}
		

	}

}
\\\\\\\\\\\\\\\\\\\
