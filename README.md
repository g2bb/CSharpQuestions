# CSharpQuestions

1. It can be used to organize classes or make sure you don't run out of class or method names
2. Value types help keep your data organized by distinguishing between simple numbers, strings, or boolean. This also means they can act differently and acomplish different tasks
3. These contain refrences to data whereas value types contain the data themselves
4. This makes it possible for client code fo create objects that are auto implemented into your code
5. Allows for syntax to rlease unmanaged resources
6. A type that can be multiple things such as an int or a string without explisitly stating that it is one or the other
7. Checks if the type of an object is compatable with another type
8. Allows a class or method to be defined with a type T
9. Public,Private,Protected,Internal,&ProtectedInternal Access Specifiers,  
10. Yes by using the params keyword
11. using `foreach (<Value Type> name in Array);`
12. Nulls can represent all the values of an unterlying as well as a null value. The prupose is to allow you to represent a type that hasn't been defined
13. Used to assign name or string values to constants to make it easier to read/maintain
14. The ability to create a class that inherits the attributes of another existing class
15. No
16. Works much like a cast, except it will return an exception if it fails
17. An instance of a class created dynamically
18. Structs: are value types, can not have null refrences, and don't support inheritance. Class: refrence types, Can have null refrences, can support inheritance
19. Breaks terminate a loop moving on to the next part, Continues skip the rest of the loop, but the loop keeps going (ie: Loop{1,2,3, continue, 4,5,6} runs 1,2,3 and then restarts the loop)
20. used to refer to the current instance of the class
21. Try contains a block of code that may cause an exception, and Catch contains the block of code that is executed when that exception happens
22. by using Try, Catch, and Finally in that order
23. Finally is executed when try/catch finishes regardless of the outcome, and is used to release system resources
24. Array: Can only have one specific type of item or element, can only store one datatype, can't accept null, belongs to System.Array
    ArrayList:  can have more than one type of item or element, can store multiple datatypes, can accept nulls, belings to System.Collections
25. A dynamically created class
26. A part of C# used to initialize data members of a new object
27. Var can be used when implisitly types are allowed by the method scope, and are their type is determined by the compliler
28. a class that is inherited by subclasses that will either implement or modify its methods
29. contains only the declaration of methods, properties and events but not the implementation
30. a code block containing a series of statements
31. A member tha allows read/writing of the value of a private field
32. a tool used to describe the scope of accessability of an object and it's members
33. Public: an be accessed from anywhere, Private: can be accessed only from within the class or struct they're declared in, Protected: can be acessed only from within the class or struct and the classes inherited from it, Internal: can access modifiers in the class it is defined in & access within the same assembly level, Protected Internal: can access anywhere in the same assembly, or class as well as the inherited classes
34. A group of objects that can expand or shrink dynamically
35. represents a collection of key-and-value pairs organized based on the key's hash code
