# Java-Experiment-1

# Arithmetic Operations

## Aim:
  To write a Java program to perform arithmetic operations on the given numbers.
  
## Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class and name it ArithmeticOperations.

Step 3 : Using Scanner, we can input numbers from the user.

Step 4 : Write the logic for the program using arithmetic operations.

Step 5 : Display the operations done the input numbers in the terminal.

## Program:
```
Developed by: S.Sham Rathan
Register.no : 212221230093

import java.util.Scanner;
public class Arithmetic
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int add=a+b;
        int sub=a-b;
        int mul=a*b;
        int div=a/b;
        int rem=a%b;
        System.out.println("Addition of two numbers:"+add);
        System.out.println("Subtraction of two numbers:"+sub);
        System.out.println("Multiplication of two numbers:"+mul);
        System.out.println("Division of two numbers:"+div);
        System.out.println("Remainder of two numbers:"+rem);
    }
}
```

## Output:
![image](https://github.com/ShamRathan/Java-Experiment-1/assets/93587823/4bb08307-50e4-43fe-960b-0c23877bbaae)



## Result 
  We have successfully created a Java program to display the arithmetic operations on numbers.
