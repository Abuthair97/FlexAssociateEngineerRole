# Flex Associate Engineer Role Preparation



## what is Java ?
- Java is high level programming language that was developed by James gosling in the year of 1982 . it is based on the principle of Object oriented Programing and develop large application

 ## Why is Java a platform independent language? 
 - Java language was developed  so that it doesn't depend on any hardware or software because the compiler compiles the code and it converts it into plateform indipendent byte code which can run on any multiple system
 - The only condition to run that byte code is for the machine to have a runtime environment (JRE) installed in it.

## what are primitive types of Java? 
- byte
- short
- int
- long
- boolean
- char
- float
- double

## Why Java is not pure OOPS language?
- Java is not not pure object oriented programming language because it supports primitive types like byte , char ,short , long , int , double , float , boolean 
- static methonds can directly access in main without using object

## How does java memory is stored ?
- Heap memory 
- Stack memory

## Stack Memory 
- Stack memory is the portion of memory which was assigned to every individual  program and it was fixed
- when we write a java pragram all the variables methods etc are stored in stack memory

## Heap Memory 
- Heap memory is the portion of memory with is not allocate of the program but it will be available for the use of  java program when it is required mostly on run time
- when we create any object in Java program then that object is created in heap memory

## what is Data Encapsulation ?
- Encapsulation is an Object oriented programing concept which is used to bundling the data attributes and  there behaviors into a single unit
- it is used to hide the data from unauthorized user

## what is abstaction ?
- Abstaction in java refers to hiding the implemention details of code and exposing only the necessary information to end user

## What is Polymorphism ?
- Polymorphism is  the task that  perform single action in different ways . the word poly means many morphism means forms
- there are two types of polymorphism
- method overloading (Compile time polymorphism)
- method overriding (Run time polymorphism)

## What is overloading 
- when there are multiple functions with same name and different parameters are know as method overloading (Compile time polymorphism)

## What is method overriding 
- if the child class has the same method as declared in parent class it is know as method overriding (Run time polymorphism)

## what is inheritance 
- inheritance is important concept of OOPS . inheritance allows a class to inherit the feature (fields and methods ) from another class
- it helps in code reuseablity (the child class can use parent class method and fields )
- without inheritance we wont be able to do method overriding

## what is interface in java 
- in Java , interface specify the behaviour of the class by providing abstact type

## What is Class in java
- A class is a set of objects which shares common characteristics / behavior and common properties .

## What is Objects in Java 
- an object is a member of java class its also known as instence of the class .
  
## final, finally and finalize keywords have the same function? 
- Final keyword is used to restrict the overriding method
- Finally is block used to in try , catch . it is used to handle exceptions
- finalize is method is called so that the clean-up activity is implemented

## How would you differentiate between a String, StringBuffer, and a StringBuilder ?
- storeage area : in string , String pool serves as the storeage area . in String buffer and String Builder it is stored in heaps
- mutability : String is immutable . where as String buffer and string builder are mutable
- Efficiency : working with string is slow , string builder is fastest in programing operations , String buffer is faster than string and slow than string builder

## What are the methods of Object class and what Do they do ?
- clone() returns a copy of the object
- equals() returns true when the object is equal to object passed throught the parameter
- finalize() the garbage collector calls this method while cleaning the memory
- getClass() returns the runtime class of the object
- hashCode() returns the hashcode of this object
- notify() sends notification to single thread waiting for object monitor
- notifyAll() sends notification to all thread waiting for object monitor
- toString() return String representation of the object
- wait() it forces the current thread to wait the specific amount of time untill the another thread calls notify or notify all on this object


## What is the difference between hashCode() and equals()
- equals() is used to test the equality of the object based on their on Content , while hashCode () is used to generate  a  numerical representation of the object's state.
- hashCode() is return a unique generate a number representing a object's state . it should be compare to equals() to ensure the consistency of comparisons


## What is Enum
- A enum is type of class that allows to specify  a set of predefine constant values.
- to create such class we have to use keyword enum

## Static Binding
- Static binding is also know as early binding , occurs during compile-time
- In static binding the compiler determin which method used called based on type of variable or reference used to invoke this method
## Dynamic Binding
- Dynamic binding is also know as late binding , occurs during runtime
- method resolution is based on the actual type of object at runtime . enabling polymorphism behavior and method overriding 

## what are types of access pecifier ?
- Public :Accessable from everywhere
- private : Accessable only within same class
- protected : Accessable only within same package and subclass
- default : accessable only within same package

