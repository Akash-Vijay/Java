# Basic Java Problems

1. Write a program to print whether a number is even or odd, also take input.

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
