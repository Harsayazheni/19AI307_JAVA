# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To Create a java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder

## ALGORITHM :
1.  Start the Program
2.	Import `Scanner` and define class `replace`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a string `str` from user input
4.	Create a `StringBuilder` object `sb` initialized with `str`
5.	Use the `replace()` method to replace characters from index 1 to 3 with "Java"
6.	Print the modified string using `sb.toString()`
7.	End






## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: Harsayazheni P Y
RegisterNumber: 212222040052
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class StringBuilderAppend {
public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    String input = scanner.nextLine();
    scanner.close();

    StringBuilder sb1 = new StringBuilder(input); // Initialize with input
    sb1.append("s");

    System.out.println("sb1 = " + sb1.toString());
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/53a996d8-1671-4f83-af4c-31a18898a235)




## RESULT:
Thus the java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder was executed successfully.



