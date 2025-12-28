Java variable:
variables are containers used to store data (such as numbers, text, or Boolean values.)in memory. Variables define how data is stored, accessed, and manipulated.
Example of variable
public class Main{
    public static void main(String[] args)
    {
        String studentName="kittu";
        int studentID=523;                            declaring(initialising)the variables
        int studentAge=24;
        float studentFee=45.00f;
        char studentSection=‘A’;
System.out.println("Student name: " + studentName);
System.out.println("Student id: " + studentID);
System.out.println("Student age: " + studentAge);                    display the variables
System.out.println("Student fee: " + studentFee);
System.out.println("Student grade: " + studentSection);


    }
}
Three types of variable are there in the variable 
* Local Variables: Declared inside a method, constructor, or block. Accessible only within that block.
* Instance Variables: Declared inside a class but outside any method. Each object of the class has its own copy.
* Static Variables: Declared with the static keyword inside a class. Shared by all objects of the class.
* Final Variables: Declared with final keyword. Value cannot be changed once assigned.

Local Variables : ee method Kani constructor Kani block yoke class lo mathrame declare chestundi
A variable defined within a block, method, or constructor is referred to as a local variable. Declared within a method, constructor, or block of code. They are only accessible within that specific scope and must be initialized before use.
import java.io.*;

class Geeks {
    public static void main(String[] args)
    {
        // Declared a Local Variable
        int var = 10;

        System.out.println("Local Variable: " + var);
    }
}
* Instance Variables (Non-Static Fields): I
* nstance variables are known as non-static variables and are declared in a class outside of any method, constructor, or block. 
* Declared within a class but outside any method, constructor, or block. Each object (instance) of the class gets its own copy of these variables. They are created when an object is instantiated and destroyed when the object is destroyed.
* class Geeks {
*     // Declared Instance Variable
*     public String geek;
*     public int i;
*     public Integer I;
*     public Geeks()
*     {
*         // Default Constructor
*         // initializing Instance Variable
*         this.geek = "Sweta Dash";
*     }
* 
*     // Main Method
*     public static void main(String[] args)
*     {
*         // Object Creation
*         Geeks name = new Geeks();
* 
*         // Displaying O/P
*         System.out.println("Geek name is: " + name.geek);
*         System.out.println("Default value for int is "+ name.i);
*       
*         // toString() called internally
*         System.out.println("Default value for Integer is: "+ name.I);
*     }
* }
* Static Variables (Class Fields): Declared with the static keyword inside a class but outside any method. There is only one copy of a static variable per class, shared by all instances. 
* import java.io.*;
* 
* class Geeks {
*     
*     // Static variable
*     static String geek = "Sweta Dash";
*   
*     public static void main(String[] args)
*     {
*         // Access static variable without creating an object
*         System.out.println("Geek Name is: " + Geeks.geek);
* 
*         // static int c = 0; 
*         // Error: static variables cannot be declared inside a method
*     }
* }



