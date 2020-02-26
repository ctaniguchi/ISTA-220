# Chase Taniguchi
## C#_HW_09	
### February 11, 2020


1. The enum keyword followed by the symbols representing the legal values, defines
an enumeration.
2. enum Ranks { Private = 1, Corporal = 2, Sergeant = 3}
3. Ranks.Chase = Ranks.Corporal
Console.WriteLine(Chase);
4. enum Ranks { Private = 1, Corporal = 2, Sergeant = 3}
Ranks a = Ranks.Corporal
Console.WriteLine((int)a); //prints out "2"
5. After the enum name, enter a colon followed by the type.
6. A structure is a value type, so it is stored on the stack. Similar
to a class, it can have its own field, methods, and constructors. Use structures for small data
values.
7. Some differences are you can't use a default constructor with structures, 
class is a reference type, stack vs heap.
8.  Structs are stored on the stack. Enums are also stored on the stack since they 
are a value type.
9. Fields are MinValue and MaxValue, methods are CompareTo(), Equals(), GetHashCode(),
GetTypeCode(), Parse(), ToString, TryParse().
10. 
struct DOD
{
	public string army, navy, airForce, marines;
}
11. You can't create a default constructor for a struct because the compiler always
generates one for structs.
12. CIL(Common Intermediary Language) is psuedo-machine code that is converted into
machine readable instructions. The CLR(Common Language Runtime) provides a safe and 
secure environment for your application code in the form of a virtual machine.

