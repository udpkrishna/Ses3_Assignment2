package AssignmentPack;

import java.util.Scanner;

public class Ses3Assignment3 {
	public static void primeNot(int num)
	{
		int half=num/2;
		int flag=0;
		for (int i=2;i<=half;i++)
		{
			if (num%i==0)
			{
				flag=1;
				break;
			}
			
		}
		if (flag==0)
		{
			System.out.println("Entered no "+num+" is prime");
		}
		else
			System.out.println("Entered no "+num+" is not prime");
	}
	public static void main(String[] args) {
		System.out.println("Enter a no:");
		Scanner sc= new Scanner(System.in);
		int i = sc.nextInt();
		Ses3Assignment3.primeNot(i);
	}
}
