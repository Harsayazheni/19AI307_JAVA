# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :
1.  Start the Program.
2.	Import `Scanner` and define class `demo`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a line of text into `String` variable `str`
4.	Print "The size of the String is " + `str.length()`
5.	End




## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: Harsayazheni P Y
RegisterNumber: 212222040052
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class StringEqualityCheck { public static void main(String[] args) { Scanner scanner = new Scanner(System.in);
    String string1 = scanner.nextLine();

   
    String string2 = scanner.nextLine();

    
    boolean areEqual = string1.equals(string2);

   
    System.out.println(areEqual);

    scanner.close();
}
```






## OUTPUT:
![Uploading image.png…]()



## RESULT:
Thus the java Program to read input and print length of the string in java was executed successfully.

