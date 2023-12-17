# Branching-and-Looping-Statements
1)write a java program to print numbers from10 to 50 using for/while loop?
import java.util.Scanner;
public class Main{
	public static void main(String[] args) {
		int startingNumber = 10;
		int endingNumber = 50;
		Scanner obj=new Scanner(System.in); 
		while(startingNumber <= endingNumber) {
			System.out.println(startingNumber);
			startingNumber++;
		}
		
	}
}
2)Write a program that find given number is positive or negative?
import java.util.Scanner;
public class Main{
public static void main(String[] args) 
    {
        int n=27;
        Scanner Object= new Scanner(System.in);
        System.out.print("Enter the number");
        if(n > 0)
        {
            System.out.println("The given number is Positive");
        }
        else if(n < 0)
        {
            System.out.println("The given number is Negative");
        }
        else
        {
            System.out.println("The given number is neither Positive nor Negative ");
        }
    }
}
3) write down the program to reverse down a given number in java
input=876
output=678
import java.util.Scanner;
public class Main {
    
    public static void main(String[] args) {
        Scanner obj = new Scanner(System.in);
        int number = obj.nextInt();
        int rev = 0;
        
        while(number != 0) {
            int rem = number % 10;
            rev = rev * 10 + rem;
            number /= 10;
        }
        
        System.out.println(rev);
    }
}

4)Write a java program to find the smallest number among three numbers?
import java.util.Scanner;
public class Main{
public static void main(String[] args) {
    int a,b,c;
        Scanner Obj = new Scanner(System.in);
        System.out.println("Enter the first number:");
        a = 23;
        System.out.println("Enter the second number:");
        b = 67;
        System.out.println("Enter the third number:");
        c = 77;
        if(a < b && a < c)
        {
            System.out.println("The smallest number is:"+a);
        }
        else if(b < c)
        {
            System.out.println("The smallest number is:"+b);
        }
        else
        {
            System.out.println(" The smallest number is:"+c);
        }
 
    }
}
5)Write a Java program that takes the purchase amount as input and calculates the final payable amount after applying the discount.

1. If the purchase amount is less than 500, no discount is applied.

2. If the purchase amount is between 500 and 1000, a 10% discount is applied.

3. If the purchase amount is greater than 1000 a 20% discount is applied.
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
   {
        Scanner obj=new Scanner(System.in);
        System.out.println("Enter the Amount:*);
        int amount =obj.nextInt();
        double discount = 0;
        if(amount<500)
        {
            System.out.println("The final pay for the given amount is(No Discount): "+amount);

        }
        else if (amount>=500 && amount<1000)
        {
            discount=amount *0.1;
            System.out.println("The final pay for the given amount is after 10% discount is:+(amount-discount));
        }
        else
        {
            discount=amount*0.2;
            System.out.println The final pay for the given amount is after 20% discount is:*+(amount-discount));
       }
   }
}
6)Write a java program to print the bellowed pattern 
55555
54444
54333
54322
54321
import java.util.Scanner; 
class pattern 
{ 
  public static void main(String args[]) 
  { 
    int n; 
    Scanner obj=new Scanner(System.in); 
    n=obj.nextInt(); 
    for(int i=0;i<n;i++) 
    { 
      for(int j=n;j>=1;j--) 
      { 
        if((i+j)>n) 
          System.out.print(j); 
        else 
          System.out.print(n-i); 
      } 
      System.out.println(); 
    } 
  } 
}
