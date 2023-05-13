# EXP-1 java program to print the Arithmetic operations

## AIM:
To write java program to print the Arithmetic operations.

## PROCEDURE:
### STEP1:
Import the required packages.
### STEP2:
Get the input for arithmetic operations from the user.
### STEP3:
Perform arithmetic operations using the arithmetic operator.
### STEP4:
Display the result of the operations using print function.
### STEP5:
Stop the execution.

## PROGRAM:
```java
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int num1,num2;
        System.out.print("Enter Two Numbers for Arithmetic Operations:");
        num1=sc.nextInt();
        num2=sc.nextInt();
        //Arithmetic Operations
        int sum=num1+num2;//Addition
        int diff=num1-num2;//Subtraction
        int prod=num1*num2;//Product
        int div=num1/num2;//Division
        int mod=num1%num2;//Modulus
        System.out.println("Sum of "+num1+" and "+num2+" = "+sum);
        System.out.println("Diffrence of "+num1+" and "+num2+" = "+diff);
        System.out.println("Product of "+num1+" and "+num2+" = "+prod);
        System.out.println("Division of "+num1+" and "+num2+" = "+div);
        System.out.println("Modulus of "+num1+" and "+num2+" = "+mod);
    }
}
```
## OUTPUT:
![image](https://github.com/Karthikeyan21001828/JAVA_EXP01/assets/93427303/27d459bb-54b2-4716-b992-ab8691043310)

## RESULT:
A java program to print the Arithmetic operations has been executed Successfully.

