# <p align="center">EXP-1-java-program-to-print-the-Arithmetic-operations...</p>

## AIM:

To write a java program to print the arithmetic operations.

## ALGORITHM:

### Step 1:

Import the necessary packages.

### Step 2:

Get the two values from the user.

### Step 3:

Calculate the basic arithmetic operations using two variables.

### Step 4:

Print the result.

### Step 5:

End the program.

## PROGRAM:

```java

Name : Anto Richard. S
Register Number : 212221240005
Java program to print the arithmetic operations.

```

```java

import java.util.*;
public class ArithmeticOperations
{
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        int a,b;
        System.out.print("Enter your first number: ");
        a = s.nextInt();
        System.out.print("Enter your second number: ");
        b = s.nextInt();

        int sum = a+b;
        int sub = a-b;
        int multiply = a*b;
        int divide = a/b;
        int rem = a%b;

        System.out.println("Sum of two numbers : "+sum);
        System.out.println("Difference of two numbers : "+sub);
        System.out.println("Product of two numbers : "+multiply);
        System.out.println("Quotient of two numbers : "+divide);
        System.out.println("Remainder of two numbers : "+rem);
    }
}

```

## OUTPUT:

![o1](https://github.com/anto-richard/-EXP-1-java-program-to-print-the-Arithmetic-operations/assets/93427534/cdde33ba-1f5d-48ed-bd44-dcfc4f17ad65)

## RESULT:

Thus the java program to print the arithmetic operations is written and implemented successfully.

