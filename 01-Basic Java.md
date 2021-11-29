# Basic Java Problems

<br>

1. Write a program to print whether an inputted number is even or odd.

```java
import java.io.*;
import java.util.Scanner;

public class Evenorodd {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        System.out.print("Enter any integer: ");
        int num = input.nextInt();

        if (num%2 == 0) {
            System.out.println("The number is Even");
        }
        else {
            System.out.println("The number is Odd");
        }
    }
}
```
<br>

---

<br>

2. Take a name as input and print a greeting message for that name.

```java
import java.io.*;
import java.util.Scanner;

public class Greetings {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter your name: ");
        String name = input.next();
        System.out.println("Hello, " + name);
    }
}
```
<br>

---

<br>

3. Write a program to input principal, time, and rate (P, T, R) from the user and find Simple Interest.

```java
import java.io.*;
import java.util.Scanner;

public class Simpleinterest {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter Principal Amount: ");
        float principalAmount = input.nextFloat();
        System.out.print("Enter Time Rate: ");
        float timeRate = input.nextFloat();
        System.out.print("Enter Rate of Interest: ");
        float interestRate = input.nextFloat();

        float simpleInterest = principalAmount * (1 + (timeRate *interestRate));

        System.out.println("The Simple Interest is " + simpleInterest);
    }
}
```
<br>

---

<br>

4. Take in two numbers and an operator (+, -, *, /, %) and calculate the value. (Use if conditions)

```java
import java.io.*;
import java.util.Scanner;

public class Basicoperations {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter two numbers: ");
        float num1 = input.nextFloat();
        float num2 = input.nextFloat();
        System.out.print("Enter an operator (+ , - , * , / , %): ");
        char operator = input.next().charAt(0);

        if (operator == '+') {
            float sum = num1 + num2;
            System.out.println("Sum = " + sum);
        }

        else if (operator == '-') {
            float difference = num1 - num2;
            System.out.println("Difference = " + difference);
        }
        
        else if (operator == '*') {
            float product = num1 * num2;;
            System.out.println("Product = " + product);
        }

        else if (operator == '/') {
            float quotient = num1 / num2;
            System.out.println("Quotient = " + quotient);
        }
        
        else if (operator == '%') {
            float remainder = num1 % num2;
            System.out.println("Remainder = " + remainder);
        }

        else {
            System.out.println("Invalid operator. Try Again !");
        }  
    }
}

```

<br>

---

<br>

5. Take two numbers as input and print the largest number.

```java
import java.io.*;
import java.util.Scanner;

public class Largest {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter two integers: ");
        int num1 = input.nextInt();
        int num2 = input.nextInt();

        if (num1 > num2) {
            System.out.println(num1 + " is greater");
        }

        else if (num2 > num1){
            System.out.println(num2 + " is greater");
        }
        else {
            System.out.println("Both are equal !");
        }
    }
}
```
<br>

---

<br>

6. Input currency in rupees and output in USD.

```java
import java.io.*;
import java.util.Scanner;

public class Currencyconverter {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter IND Currency: ₹ ");
        float currencyInd = input.nextFloat();
        System.out.println("Converted Currency: $ " + currencyInd * 0.013);
    }
}
```
