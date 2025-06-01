# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Harsayazheni P Y
RegisterNumber: 212222040052
*/
```

## Sourcecode.java:
```
class Student
{
    String name;
    int roll_no;
}
public class Main {
    public static void main(String[] args) {
        Student obj= new Student();
         obj.name="John";
        obj.roll_no=5;
      System.out.println(obj.name+" "+obj.roll_no);
    }    
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/6bcd09bc-d13a-47c7-8cd8-ee29c4110ba1)




## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
