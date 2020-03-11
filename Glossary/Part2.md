# Glossary Part 2 - C

**Call Stack** - A list of methods that have been called in the order in which they were called.  Typically, the most recently called method (the current method) is thought of as being at the top of the call stack.


**Casting** - Casting is the conversion of one type of one type to another type.  Typically, casting is used to convert an object reference to either a subtype (for example casting an Animal reference to a Horse), but casting can also be used on primitive types to convert to a larger type to a smaller type, such as from a long to an int.


**char** - A 16-bit unsigned primitive data type that holds a single Unicode character.


**Character literals** - represented by a single character in single quotes such as 'A'.


**Child class** -  _see Derived class_


**Class** - definition of a type.  It's the blueprint used to construct objects of that type.


**Class members** - things that belong to a class including methods (static and non static), variable (static and non static), nested classes (static and non static).  Class members can have any of the four access control levels (public, protected, default(package) and private).


**Class methods** - often referred to as a static method, may be accessed directly from a class without instantiating the class first.


**Class variable** - _See static variable_


**Collection** - An object used to store other objects. Collections are also commonly referred to as containers.  Two common examples of collections are HashMap and ArrayList.


**Collection interface** - defines the public interface that is common to Set and List collection classes.  Map classes (such as HashMap and Hashtable) do not implement Collection, but are still considered part of the collection framework.


**Collection framework** - Three elements (interfaces, implementations and algorithms) create what is known as the collection framework, and includes Sets (which contain no duplicates), Lists (which can be accessed by an index position), and Maps (which can be accessed by a unique identifier).


**Comparison operators** - perform a comparison on two parameters and return a boolean value indicating if the comparison is _true_.  For example, the comparison 2<4 will result in _true_ while the comparison 4==7 will result in _false_.


**Constructor** - A method-like block of code that is called when created (instantiated).  Typically, constructors initialise data members and acquire whatever resources the object may require.  It is the code that runs before the object can be referenced.


**continue statement** - The continue statement cause the current iteration of the innermost loop to cease and the next iteration of the same loop to start if the condition of the loop is met.  In the case of using a continue statement with a _for_ loop is met.  In the case of using a _continue_ statement with a _for_ loop, you need to consider the effects that the continue has on the loop iterator (the iteration expression will run immediately after the _continue_ statement).
