# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to reverse a given string.

For example:

| Input | Result |
|------|--------|
| welcome | Reversed string: emoclew |

---

## AIM:


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3. Create a Scanner object to read input from the user.  
4. Read the input string using `next()`.  
5. Create a `StringBuilder` object and pass the input string to it.  
6. Use the `reverse()` method of StringBuilder to reverse the string.  
7. Print the reversed string.  
8. End the program.

---





## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: MYVIZHI S
RegisterNumber: 212224040209 
*/
```

## SOURCE CODE:
```java
import java.util.*;

class prog{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        String a = sc.next();
        StringBuilder sb = new StringBuilder(a);
        System.out.println("Reversed string: " + sb.reverse());
    }
}
```






## OUTPUT:

<img width="692" height="297" alt="image" src="https://github.com/user-attachments/assets/3e79d8f2-9173-4a9a-bc56-42012a6338f3" />


## RESULT:
Thus, the Java program to **reverse a given string** was executed successfully.
