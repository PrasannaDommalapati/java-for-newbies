# public static void main(String args[]) Explanation

JVM always looks for a specific signature of a method to start running an application/program, and that would be ```public static void main(String args[])```. Here args is an argument of type String array. Name of the argument(parameter) can be anything, not necessarily ```args```.

Also with the introduction of java args, instead of writing ```String args[], String… args``` can be used. Keep learning to know more about each and every keyword.


```
public clas FirstJavaProgram {
    public stastic void main(String args[]) {
        
        System.out.println("Welcome to Java Programming!!!");
    }
}
```
In the above application example, we are using public static void main. Each word has a different meaning and purpose which is detailed below.


## public

This is an ```Access Modifier```, which can be used to define who can have access this method. ```public``` means this method will be accessible by any class(Only the classes who can access this class).  

## static

Static ss a keyword which identifies the class related thing. It means the given Method or variable is not instance related but Class related. It can be accessed without creating the instance of a Class.

## void

Is used to define the Return Type of the Method. It defines what the method can return. Void means the Method will not return any value.

## main

Main ss the name of the Method. This Method name is searched by JVM as a starting point for an application with a particular signature only.

## String args[]/String... args

It is the parameter to the main Method. Argument name could be anything.









