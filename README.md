# Branching-and-Looping-Statements
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
5)Write a java program to print the bellowed pattern 
55555
54444
54333
54322
54321
import java.util.Scanner;
public class Main{
 
     public static void main(String []args){
       Scanner obj=new Scanner(System.in);
       int f,i,j;
       System.out.println("Enter number of rows");
       f=obj.nextInt();
     
       for(i=f;i>=1;i--)
       {
           for(j=f;j>=1;j--)
           {
               System.out.print(i>j?i:j)
           }
           System.out.println();
       }
     
     
     }
}

