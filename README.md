You can use a text editor, compile and run code in commandline cmd.exe.

Java procss
=============
Write java code -> pass to compiler -> run program -> program ends

Set up environment using Eclipse
=================================
Download Java from the Oracle website and add a path in the system variable of your computer.
Download an IDE such as Eclipse from eclips.org. Select workspace (e.g. deskop) and create a project - file > new > java project with name. Click next. Uncheck create module.info. Java file. Click finish. Expand folder in package explorer pane N.b JEE systm library an src folder are created. Add library, naviate to java folder. Change compiler compliance level to your version of java

Create a java file
------------------
Select src folder
Create java class by clickig new java class button
enter class name.java

N.b. package is an identifier associated with clases. 

Enter package name checkbox to create method stub public static, void main (main entry point for the application). Click finish. 

N.b. you only need one for the application uncheck

N.b. if a class is in the same packae you don't need to import it. 

Use mc dot to use property or execute methods from other class

N.b. if you expand the class in package explorer you can see the properties and methods attached to the class.

Add label or button
--------------------
In the palette column click J label and then click in the application (next column) to past it.

N.b. you can see the labels properties in the properties area of the scree. You can modify properties in this area.
N.b. click the source tab to see the code for the label
N.b. in the compoents section you can see the structure.

Other components include checkbox Right click > add event handler > action > action perform

Nb. The order in the code matters.Make sure in the code you create element before trying to access it. Radio buttons these can be made into a groups. Select all > right 
click button group > new standard. you can now only select one button in the application.

Layouts
-------
Select layout under layouts heading in palette.

Connect UI elements to code
------------------------------
e.g. input field changes label
in design tab get variable names of the elements
Click source tab

N.b If you double click on a button in design and go to source part of the file code is created for you add soe custom code to this 
e.g. label.setText('hi' + textField.getText());

Listner classes
---------------
1. Define listener. 

RadioListener listener = new RadioListener();

2. In the element code referenc the listener

item2.addActionListener(listener);

3. Create a listener class

Create a user interface
-------------------------
Using Swing which is an extension of eclise:
1. Go to help > install new software
2. In work with box entr https://download.eclipse.org/windowbuilder/latest and press return. Check the two boxe and click next.
3. Click next again accept licence agreement and click finish. All swing components ill b installed. 
N.b. you can check progress in the bottom right of the screen
4. Restart software for changes to take affect. N.b you will now see new create new visual class option menu for swing.
5. In option menu select swing > application window. Enter a name java and click finish. N.b. contains function, methods at bottom of screen click design tab
6. Run application

Handle java errors
------------------
Create a method that handles exception throws IOException.  Call the method from the main method using a try catch block e.g. 

try {
loadfile("files.txt");
} 
catch(IOException e) {
system.out.println(e);
}

Add/remove components at runtime
---------------------------------
Create the element code inside the action listener method

To delete use frame.getContentPane().remove(label);

N.b. you need to revalidate and repoint the layout

frame.revalidate();
frame.repoint();

Testing
-------
JRE unit

Publish a runnable JAR file
============================
To export your project from Eclipse to local machine:
1. file > export
2. Open java folder and select runnable jar file
3. In launch configuration dropdown elect project
4. browse for eport destination and enter filename
5. select a library handling setting (e.g. extract required libraires into generated jar)
6. click finish
7. open the new jar file to run your application

N.b. you can use a jar file in another project.

N.b. Select jar file rather than runnable jar file to save

use a jar file  in another project
---------------------------------------
To use a jar file  in another project:
1. right click > properties > ava buildpath
2. select libraries tab
3. click classpath and click add external jars button
4. select the jar file
5. click apply and close. The file should now show in the referenced libraries folder
