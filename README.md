# Factorial
Java program to check given number is Factorial or Not
import java.util.Scanner;
public class Factorial
{
  public static void main(String [ ]args);
     {
         int i,factorial=1,number;
         System.out.println("Enter the number to which you need to find the factorial:");
         Scanner fact= new Scanner(System.in);
         number= fact.nextInt();
         for(i=1;i<number;i++)
         {
             factorial=factorial*i;
          }
          System.out.println("Factorial of the given number is:"+ factorial);
      }
}
