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
