Java OOP (object oriented programming)
=======================================
Class
------
A template for objects An object is created from a class. Declare clss using the class keyword then within the clss add avriables, add constructor (with same name as class) 
N.b. constructor can take arguments which can be assigned to a variable. Class hould always start with an uppercase first letter and the name of the java file should match 
the class name. A package in Java issued to group related classes

The java API is a library of prewritten classes (you can also define your own). To use a class or a package from the library you need to use the import keywor. 

It is possible to inherit attributes and methods from one class to another using the extends keyword.

Polymorphism occurs hen we have many classes tat are related to each other by inheriance.

Object
------
An object is an instance of a class. Create by using the keyword new. Objects are combinations of data and procedures.  Iherits variables and mehtods from class.  To create an 
object specify type, variale name, java keyword and constructor e.g

car myFirstCar = new car();

To access attributes create an object of the class and use the dot syntax. You can modify or overwirte attribute values. If you do not want the ability to override existing 
values, declare the attribte as final. Abstract class is a restrictd class that cannot be used to crate objects. To access an abstract class it must be inherited from
another class. Abstact methods can only be used in an abstract class

An interfact is a completely abstract class that is used to group related methods with empty bodies.

Method
------
A method is a group of statements that can be referred to by name. Methods are attached to a class.

A method is written within class and at the end of the method specifies object behaviour It is called to get information back.

N.b. if it is not to return anything use void

N.b. static method is attached to a class and can be accessed ithout createing an object of th class. Non static method is attached to an instance of a class - can only be accessed
by objects.

To create a method speciy method return type, method name within method add java keyword

public int howFastDosItGo() {
     return max Speed;
}

Some methods take arguements

Access modifiers
-----------------
Access modifiers are used to group related functionality into classes. 

public - can be called in the class
private
hidden - unvavailable to external classes. It is possible to access them if you provide public get and set methods.

Nb. by default methods are public.

enum
-----
an enum is a special class that represents a group of constants. To create an enum use th eum keyword. Constants within the enum should be upercase and seperated by comma.

Enum can be accesed using the dot syntax. They can be accessed in a class, in a witch statement.

Enum can also be created inside a class

Nb. an enum cannot be used to create objects and it cannot extend other classes but it can implement interfaces.

Logic
------
Logic conrols which instructions are executed. Conditional statements if els, for loops etc.

Logic is used for 
cheking equality
making a comparison
check if a condition is true.

Dates
-----
Java does not have built in date class but you can iport java.time package to work with the date and time api.

Threads
-------
A thread allows a program to do multiple things at the same tie without interrrpting the ain program.

Collections - arrays and array lists
--------------------------------------
Array:
An array has index and values. To declare an array enter data type, brackets and a name e.g

int [] bunchOfIntegers

N.b. need to let compiler know the siz of the array before using it and assign items to do it.

string [] donuts = new string [1];
myBoxOfDonuts[0] = Jam;
myBoxOfDonut[1] = chocolate;

N.b. retrieve items from array using the index

n.b. arrays cannot grow or shrin in size so the array lists can be used instead.

Array list:
An array list is a resizable array found in Java.util package.

ArrayList <Type> VariableName = new ArrayList <>();

YOu can use any available methods.

Nb. no need to specify size.

Two dimensional array:
Two dimensional array is an array within an array. To add items eter name then dot then add method and pass in data e.g.
madDictators.add('John Doe');

Use index to retrieve items entering name dot get method passin in index value.

All methods can be found at http://docs.oracle.com/javase/7/docs/api/java/util/ArrayList

Inheritance
---------------
Inheritance build on existing classes and use their functionalty. Create new classes built on existing classes. The new class will have access to inherit
its pareents methods and fields. The new class can expandd its functionalty.  To create an inheritance use the keyword extends e.g. 

public class sportsCar extends car {}

use the super plus dot to call the parent's method.

Interface
----------
Interface give classes and objcs functionlaity that doesnt com from the parent. n interface is a set of skills that exist outside the class.  A class implements an interface using the implements keyword e.g

public class Emporor implements Human {}

A common interface is a listener

