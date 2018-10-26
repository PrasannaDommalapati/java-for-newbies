
# Class and Object

## Topics to be covered
* Class Definition
* Syntax of delaring a Class
* Example of Java class
* Rules Applicable
* Object Definition
* How to create an Object of a Class
* How to access member of a class
* Highlights

## Class:
A Class is a template for creating objects which define its state and behaviour. A class contains field(s) and method(s) to define the state and behavior of its object.

## Syntax of a class
```
<Access Modifier> class <Class Name> extends<Super Class Name> implements <Interface Name> 
{


}
```

```ACCESS MODIFIER :``` Defines who in the java woirld can access this class and members of the class.

```CLASS NAME :``` Unique name for the class in a specific package

```SUPER CLASS NAME :``` Name of the class which given class extends. (```extends``` keyword is used for this purpose)

```INTERFACE NAME :``` Name of an interface which above class implements. (```implements``` keywod is used on this purpose)

## Internal Structure of the class
```
<Access Modifier> class <Class Name> extends <Super Class Name> imp[lements <Interface Name>
{
    <static initializer block>
    <ananymous block>
    <constructor delaratiopns>
    <field declaratisons (Static or Non-Static)>
    <method declaratisons (Static or Non-Static)>
    <Inner_class_declarations>
    <nested_interface_declarations>
    variables_inside_class(Static or Non Static)

}
```

## Example of Java Class

```
package com.pkgName;
import java.lang.*;

/*
 * As this file contains public class. Then the name of this file should be ExampleClass.java
 */
 
 public class ExampleClass {
    public int i; //this is a non static variable
    
    static {
        System.out.println("This is the static block");
    }
    
    {
       System.out.println("This is the ananomous block");
    }
    
    ExampleClass() {
       System.out.println("This is the Constructor");
    }
    
    void methodName() {
       System.out.println("This is the method");
    }
}

class AnotherClass {

}
```

Classes are written in a Java source file. A source file can contain more than one Java Class. There are some rules associated to the Java source file as listed below.

## Rules for java source file
* There can be only one public class per source code file but it can have multiple non-public classes.
* In case there is any public class present in the source code file, the name of the file should be the name of the class.
* The sequence of statements in a source code file should be package >> import  >> Class declaration.
* No Sequence rule is applied for Comments.
* Comments can be there in any part of the source code file at any location.
* Files with no public class can have any name for the class.
* Import and package statements should be applied to all the classes in the same source code file.



