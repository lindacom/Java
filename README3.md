Working with files
===================
Creating a desktop application. export project to a file with etension .jar (like .exe). This type of file can be run from the desktop.

Printing code
-------------
To print to the console in the method enter Systemout.println (variable name); then run the code  View results i the console

To print a looped array 

for (int I=0; I<breakfast.lenth; I++) {
   system.out.println(breakfast[I];
   }
   
Read data from a file
--------------------

1. Create a file in the src folder - file > new > untitled text file
2. Import file systems
3. Access file using path passing in directory and filename
4. Import list and load file into a list
5. Import exception

Scanner
=========
The scanner class is used to get user input and is found in the java.util package. You can use any of the available methods.
   
Getting data from console input to application
==============================================
Using scanner and create new instance of scanner type. e.g. name propt in console, user inputs name, console hello essag

1. Import scanner
2. Create scanner constructor and pass in parameters

```
import java.util.Scanner;

public class Review {
  public static void main (string[] args) {
     // receives input
   Scanner scanner = new scanner(system.in);
   system.out.println('enter your name');
   string name = scanner.nextLine();
   // prints input
   system.out.println("Hello" + name);
   scanner.close();
   }
   }
 ```
 
 N.b. always close scanner
 
 
