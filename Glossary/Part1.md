# Glossary Part 1

**Abstract class** - An abstract class is a type of class that is not allowed to be instantiated.  The only reason it exists is to be extended.  Abstract classes contain methods and variables common to all the subclasses, but the abstract class itself is of a type that will not be used directly.  Even a single abstract method requires that a class be marked __abstract__.




**Abstract method** - An abstract method is a method declaration that contains no functional code.  The reason for using an abstract method is to ensure that subclasses of this class will include an implementation of this method.  Any concrete class (that is, a class that is not abstract, and therefore capable of being instantiated) must implement all abstract it has inherited.


**Access modifier** - a modifier that changes the visibility of a class or member of a class (method, variable or nested class).


**Anonymous inner classes** - local inner classes that do not have a  class name.  You create an anonymous inner class by creating an instance of a new named class that is either a subclass of a named class type of an implementer of a named interface type.


**API** - Application Programming Interface. This item refers to a set of related classes and methods that work together to provide a particular capacity. The API represents the parts of a class that are exposed (through access controls) to code written by others.


**Array** - homogenous data structures implemented in Java as objects.  Arrays store more of a specific type and provide indexed access to the store.


**Automatic variables** - Also called method local or stack variables.  Automatic variables that are declared within a method and discarded when the method has completed.


**Base class** - A class which has been extended.  If class D extends class B, then class B is the base class of class D.


**Blocked state** - A thread that is waiting for a resource, such as a lock, to become available is said to be in a blocked state.  Blocked threads consume no processor resources.


**Boolean expression** - An expression that results in a value of __true__ or __false__. Typically, this involves a comparison (e.g. x > 2) or a boolean condition such as (x < 5 && y > 3), but can alsoinvolve a method with a boolean return type.


**boolean primitives** - A primitive boolean value can be defined only as either true or false. 
