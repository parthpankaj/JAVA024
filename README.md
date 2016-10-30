	import java.util.Scanner;


	public class Findlargest {

		public static void main(String[] args) {
			
			Scanner scan = new Scanner(System.in);
			
			System.out.println("Enter number 1 :");
			int num1 = scan.nextInt();
			
			System.out.println("Enter number 2 :");
			int num2 = scan.nextInt();
			
			System.out.println("Enter number 3 :");
			int num3 = scan.nextInt();
			
			
			if(num1 > num2 && num1 > num3){
				System.out.println("Highest Number is " + num1 );
			}
			
			else if(num2 > num3){
				System.out.println("Highest Number is " + num2 );
			}
			
			else{
				System.out.println("Highest Number is " + num3 );
			}
		}
		
	}
	
	




Enter number 1 :
25
Enter number 2 :
36
Enter number 3 :
89
Highest Number is 89
