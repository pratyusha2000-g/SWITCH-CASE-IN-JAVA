# SWITCH-CASE-IN-JAVA
import java.util.Scanner;
public class Main
{
	public static void main(String[] args)
	{
	    Scanner sc=new Scanner(System.in);
	    int ch;
		System.out.println("Enter 1 to say HI");
		System.out.println("Enter 2 to say HEY");
		System.out.println("Enter 3 to say HELLO");
		System.out.println("Enter your choice");
	    ch=sc.nextInt();
	    switch(ch)
	    {
	        case 1:System.out.println("YOU said HI");
	               break;
	        case 2:System.out.println("YOU said HEY");
	               break;
	        case 3:System.out.println("YOU said HELLO");
	               break;
	       default:System.out.println("INVALID INPUT");        
	    }
	    
	}
}
