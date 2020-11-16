Server side java
=================
To create a server side java app:

1. add plugin or click download packages from eclipse.org e.g. eclipse IDE for enterprise java dvelopers
2. install server e.g. Tomcat from tomcat.apache.org. download and extract core zip file. Copy folder into directory. Nb. you will need to navigate to this folder in eclipse
3. Create a new maven project. Select maven archive type web app and IO. click finish. In src > main > webapp folder you will find index.jsp file. Edit this file
<% %> tag is used for java code
<%= %> is used to inject java into htl
4. Click run. Select server type and click next
5. Specify tomcat installation directory and click next. You will se project on the riht
6. Click finish. Server rill have started in bottom of scree and app will be displayed at the top

Build JSF web applications with Java EE
=========================================
JSF (java server faces) is a framework for building dynaic web applications. It uses MVC. To create an a JSF application:

Set up the environment
---------------------
download eclipse for java ee developers (java enterprise) from eclipse.org. extract files from zip  folder to desktop

Server
------
1. download lassfish server from oracle website. This is a server
2. download java jre from java.com. this is a developmet platform
3. download java JDK

java ee.

Create a project
------------------
1. To start a project go to new project icon and select other. Expand web folder and select dynamic web project. give the project a name and click next
2. Select a server runtime enviornment e.g. oracle and click next 
3. Select create web.xml deployment descriptor file and click next
4. Yu will now see the folder structure. N.b. web content dolfer is where templates will be created. Select an htl templte and click finish
5. Create a file N.b. file should have extesion xhtl
6. go to window > web browser > defauls tystem browser then click run button. You will ee your page i the screen. Close the screen
7. Create a class - in the java resources > src folder create a class. Give it a name and select constructors for superclasses. Click inish.

Java resources folder is where java files will be created
8. Create a web container - web container is a server that communicates with web server and JSF application Click ervers tab at bottom of screen and click link to create server. Expand oracle folder.

Android development
--------------------
Install android studio (based on intelly IDEA). Download from developer.android.com/studio

1. To create and run an adroid application in an eulator:
2. click start a new android studio project
3. click phone and tablet tab, select empty activity and click next
4. enter a name and click finish
5. expand ap folder > java > name > manActivity java
6. click run > run and select app and choose deploymet environment or click create new virtual devise.
7. Choose phone and device type and click next
8. choose system image (eg. oreo) and click next
9. click finish. The virtual device will be created. Click ok you will then see the application in the emulator.
10. To edit go back to android studio and go to res > layout > activity_main.xml and make any changes
11. select run > apply changes and view file results in the emulator
