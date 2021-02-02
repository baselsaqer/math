# math
package basel;
import java.util.Scanner;
public class math {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.print("enter your number :");
		Scanner number = new Scanner(System.in);
		
		int a = number.nextInt();
		int b = number.nextInt();
		
		
		System.out.print("enter your math mark ");
		Scanner ma = new Scanner(System.in);
		char math = ma.next().charAt(0);
		
		if (math == '+')
		{
			System.out.print(a+b);
		}
		if (math == '*')
		{
			System.out.print(a*b);
		}
		if (math == '-')
		{
			System.out.print(a-b);
		}
		if (math == '÷')
		{
			System.out.print(a/b);
		}
	}
	

}
