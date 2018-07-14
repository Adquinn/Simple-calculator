//Simple-calculator
//A simple calculator in Java


import java.util.*;

public class SimpleJavaCalculator
{
    public static void main(String[] args)
    {
        int num1;
        int num2;
        String operation;
        
        Scanner inputScanner = new Scanner(Systems.in);
        
        System.out.println("Enter the first number.");
        num1 = inputScanner.nextInt();
        
        System.out.println("Enter the second number.");
        num2 = intputScanner.nextInt();
        
        Scanner outputScanner = new Scanner(Systems.in);
        
        System.out.println("Enter the operation");
        
        operation = outputScanner.next();
        
        if(operation.equals("+"))
        {
            System.out.println("The answer is:" + (num1 + num2));
        }
        
        else if (operation.equals("/"))
        {
            System.out.println(The answer is:" + (num1 / num2));
        }
        
        else if (operation.equals("*"))
        {
            System.out.println(The answer is:" + (num1 * num2));
        }
        
        else 
        {
          System.out.println("Invalid operation.");
        }
    }
}
