# Getting Started

## Topics to be covered
* How to download Java 
* How to install java
* How to download Java editors(Eclipse and Intellij), there are other alternatives too.
* How to verify that java is installed in your computer
* Our First Java Program
* how to run Java Application
  
  
## How to download Java
* Java (JDK) can be downloaded from [Here](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html).

## How to install Java

 There are no special requirements for installing java, make sure you have permissions to install software on your computer. It is similar to install any software(.exe) in windows.
 In mac double click on the downloaded (.pkg) file to launch it then click on the package icon to install software in Mac.

## How to download Eclipse and Intellij
* Eclipse can be downloaded from [Here](https://www.eclipse.org/downloads/).
* Intellij can be downloaded from [Here](https://www.jetbrains.com/idea/download/).

## Setting up the Environment Variables (Windows OS)

```Windows XP :``` To set up environment variables in Windows XP right click on the “My Computer” icon and select Properties. In the  Property window select the “ADVANCED”  tab and click on “ENVIRONMENT VARIABLES”. A window will appear where you can enter a new environment variable under System Variables by selecting New button.

```Windows 10 :``` To set up environment variables in Windows 10  right click on “Computer” and select Properties. In Property window select  “ADVANCED SYSTEM SETTINGS” and then select “ADVANCED” tab and click “ENVIRONMENT VARIABLES”. A window will appear where you can enter new environment variable under User/System Variables by selecting New button.

  Once after installing java in your computer there is a need of the environmental variables to be set for the availability of java in all directories.
  
  * ```CLASSPATH :``` This environment variable points to the location of the JDK home directory. It also contains the address of folder from where jars get loaded by ClassLoader (For more details of ClassLoader visit here)
  
  * ```path :```      This environment variable will have the location of ```JAVA_HOME\bin```.
  Example :```C:\Program Files\Java\jdk1.8.0_60\bin```
  
  * ```JAVA_HOME :``` This environment variable will point to the location of the Java home directory.
  Example :```C:\Program Files\Java\jdk1.8.0_60```
  
## How to verify that java is installed in your computer
To check weather java is installed in your computer or not from the command prompt. To get the command prompt (Windows +R) type cmd then click on enter key.

In the command prompt type ```java -version```. If java is installed in your computer. it will return with the details of java installed in your pc

Example: ```C:\Users\UserName>java -version
            java version "1.8.0_51"
            Java(TM) SE Runtime Environment (build 1.8.0_51-b16)
            Java HotSpot(TM) Client VM (build 25.51-b03, mixed mode, sharing)```

If there is any problem while installing java or setting up environmental variable, the outcome in the command prompt will be as below:

``'java' is not recognized as internal or external command, operable program or batch file.'``

## Our First Java program

```
public clas FirstJavaProgram {
    public stastic void main(String args[]) {
        
        System.out.println("Welcome to Java Programming!!!");
    }
}
```

## How to run Java Application

Java program should save with the name ```FirstJavaProgram.java``` in the folder ```C:\java-for-newbies``` directory. Here note that file name should be same as the class name.

Once the file is saved, open the command prompt and change the working directory to ```C:\java-for-newbies```. 
### Compile
Then write ```javac FirstJavaProgram.java``` in the command prompt and hit enter. If it returns as below then the program is syntactically correct.

```
C:\Users\UserName> C:\ java-for-newbies
C:\java-for-newbies> javac FirstJavaProgram.java
```
### Run

If the program compiles successfully with out any errors, the compiler creates a class file in the same directory.

Now that your  Java file is compiled we can execute the application using the “java” command as below.

```
C:\Users\UserName> C:\ java-for-newbies
C:\java-for-newbies> java FirstJavaProgram

Welcome to Java Programming!!!
C:\java-for-newbies>
```

The “java” command uses the class file name without its extension(.class).

With this, we are done creating and running our very first Java application.

