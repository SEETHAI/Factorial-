# Factorial
Java program to check given number is Factorial or Not
import java.util.Scanner;
public class Factorial
{
  public static void main(String [ ]args);
     {
         int j,factorial=1,num;
         System.out.println("Enter the number to which you need to find the factorial:");
         Scanner fact= new Scanner(System.in);
         num= fact.nextInt();
         for(j=1;i<num;j++)
         {
             factorial=factorial*j;
          }
          System.out.println("Factorial of the given number is:"+ factorial);
      }
}
