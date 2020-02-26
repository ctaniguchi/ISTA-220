# Chase Taniguchi
## C#_HW_08
### February 5, 2020


1. The difference between deep copy and shallow copy is that a deep copy contains all of the private data,
while a shallow copy might only hold references to it.
2. The value of a reference is a memory address that points to corresponding data on the heap.
3. You declare a value type by giving it a type, name, and assigning it a value.
4. You declare it by assigning the constructor with the new keyword to it.
5. No, unless you use the nullable modifier (?).
6. No, since by definition a non-null variable can't hold a value that could be null.
7. When memory is allocated on the stack for a method call, it has a defined
lifespan. When a new object is created, the memory is acquired from the heap, since
the required amount of memory and lifespan is unknown.
8. It means that all classes are themselves types of the System.Object class.
9. The ref keyword generates code that passes a reference to the argument instead 
of a copy of it.
10. The out keyword is similar to the ref keyword, except the method must 
assign a value to it before it finishes.
11. Boxing is the automatic copying of an item from the stack to the heap.
Unboxing uses the cast operation to check if you can convert the boxed value to the correct type, if it succeeds, the boxed value is returned.
12. Cast is used to specify that the data referenced by an object has the correct type for the referencing object.