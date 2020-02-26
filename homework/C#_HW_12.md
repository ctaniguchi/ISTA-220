# Chase Taniguchi	
## C#_HW_12
### February 20, 2020


1. Inheritance allows you to define shared functionalities for a group of similar classes
in one place, which saves you from having to define duplicate functionalities and properties
for each class.
2. class DerivedClass : BaseClass
3. All user defined classes inherit from the System.Object class, structs inhereit from the
System.ValueType class.
4. A compile-time error occurs.
5. You cannot, because the base class doesn't have all of the same properties and 
methods as the inherited class.
6. You cannot, because although they are both derived classes from the same
base class, they are still different types from each other.
7. Not always, because the base class does not share all of the functionality of the derived class.
8. When you want to define a new method that will have the same signature.
9. A virtual method is a method that is intended to be overridden. You would use one 
because it allows for different implementations of the same method.
10. Override allows a derived class to declare an Override method. 
11. You define an Extension Type by creating a class method and using the this keyword with the type.
12. You define it so you can reference it later.
13. Functions that use pointers or references to base classes must be able to use objects
 of derived classes without knowing it.