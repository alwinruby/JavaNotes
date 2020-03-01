# Glossary Part 1

**Abstract class** - An abstract class is a type of class that is not allowed to be instantiated.  The only reason it exists is to be extended.  Abstract classes contain methods and variables common to all the subclasses, but the abstract class itself is of a type that will not be used directly.  Even a single abstract method requires that a class be marked __abstract__.


**Abstract method** - An abstract method is a method declaration that contains no functional code.  The reason for using an abstract method is to ensure that subclasses of this class will include an implementation of this method.  Any concrete class (that is, a class that is not abstract, and therefore capable of being instantiated) must implement all abstract it has inherited.
