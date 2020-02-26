# Chase Taniguchi	
## C#_HW_11
### February 19, 2020


1. A parameter array is a feature that allows you to pass a variable number 
of parameters to a method.
2. Use a params array as the parameter, given a name and type.
3. Method name, followed by the parameter list.
4. An array has fixed values and must be created and populated.
5. Any amount, however having too many has drawbacks.
6. They do not, if they are of different type, use the object type.
7. Methods with parameter arrays can take an arbitrary list of values, while 
methods with optional parameters still has a fixed list of parameters it 
can take.
8. Define a parameter array with the type Object, as an argument.
9. 
public static double getAverage(params int[] values)
{	
	int count = 0;
	double average = 0;
	foreach (int i in values)
	{
		sumTotal += i;
	}

		return sumTotal / count(i) 
}
10.
public static double getAverage(params object[] values)
{	
	int count = 0;
	double average = 0;
	foreach (int i in values)
	{
		sumTotal += i;
	}

		return sumTotal / count(i) 
}