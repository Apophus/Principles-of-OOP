 # **FOUR MAJOR PRINCIPLES OF OBJECT ORIENTED PROGRAMMING**.
 
    There are four major principles of Object Oriented Programming namely:
       1.Encaspulation.
       2.Data abstraction.
       3.Polymorphism.
       4.Inheritance.
       
    ## Encaspulation.
      Encapsulation is an Object Oriented Programming concept that binds together the data and functions that manipulate the data, and that keeps both safe from outside interference and misuse. Data encapsulation led to the important OOP concept of data hiding.This involves restricting data access to _accessors_ and _mutators_. 
        ### Accesors.
          An accessor is a method that is used to ask an object about itself. In OOP, these are usually in the form of properties, which have, under
          normal conditions, a get method, which is an accessor method. However, accessor methods are not restricted to properties and can be any public method that gives information about the state of the object.
          
        ### Mutators
          Mutator Mutators are public methods that are used to modify the state of an object, while hiding the implementation of exactly how
          the data gets modified. Mutators are commonly another portion of the property discussed above, except this time its the set method that lets the caller modify the member data behind the scenes.
          
    ## Data Abstraction.
      This is the reduction of a particular body of data to a simplified representation of the whole. Abstraction, in general, is the process of taking away or removing characteristics from something in order to reduce it to a set of essential characteristics.
      An abstraction denotes the essential characteristics of an object that distinguish it from all other kinds of object and thus provide crisply defined conceptual boundaries, relative to the perspective of the viewer.
      
    ## Inheritance.
      In object-oriented programming, inheritance is when an object or class is based on another object (_prototypal inheritance_) or class (_class-based inheritance_), using the same implementation (inheriting from an object or class) specifying implementation to maintain the same behavior (realizing an interface; inheriting behavior). It is a mechanism for code reuse and to allow independent extensions of the original software via public classes and interfaces.
      
    ## Polymorphism.
      Polymorphism is the ability of an object to take on many forms. The most common use of polymorphism in OOP occurs when a parent class reference is used to refer to a child class object. Any Java object that can pass more than one IS-A test is considered to be polymorphic.Polymorphism
      manifests itself by having multiple methods all with the same name, but slighty different functionality. 
      There are 2 basic types of polymorphism.  **Overridding**, also called _run-time polymorphism_, and **overloading**, which is referred to as _compile-time polymorphism_.  This difference is, for method overloading, the compiler determines which method will be executed, and this decision is made when the code gets compiled. Which method will be used for method overriding is determined at runtime based on the dynamic type of an object.

