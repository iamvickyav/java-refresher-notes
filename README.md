# Java Notes

## OOPS

* Java is an object oriented programming language. Anything & everything in Object Oriented Programming is defined as **Object**.

* Java has number of **inbuilt data types** like int, char, float, double etc. 

* To create User defined data type, we have to use **Class**. Class defines blueprint from which objects are created. Class contains **properties & methods**.

* In Java, nothing can be defined outside of class (otherwise called Encapsulation). Ideally, all properties in the the class would be declared as private and will be accessed from outside via public methods

* There can be two types of relationship exist between objects. IS-A & HAS-A relationship

* IS-A relationship is otherwise called inheritance. It is how one class (sub class) inherits **properties & method** from another class (super class). Super class can control what are all properties and methods can be inherited by sub classes

| Access Modifier of super class's property/method  |  Accessible in Sub class ? |
|---|---|
|  private |  not accessible |
|  protected | accessible  |
|  public | accessible  | 

* **private** properties/method are accessible only in the declared class. **protected** properties/methods in super class are accessible from any subclass. Same can be said for **public** as well

* Subclass can also overload or override methods inherited from super class. 

* **Overloading** (otherwise called compile time polymorphism) is achieved, if the method name is same but the argument of the methods are different. Different here means, the number of parameter or type of the parameter or order of the parameter can different between two methods with same name qualified for overloading. For overloading, inheritance is not mandatory. 

* **Overriding** (otherwise called run time polymorphism) if the signature of two methods are exact match. For overriding inheritance is mandatory

