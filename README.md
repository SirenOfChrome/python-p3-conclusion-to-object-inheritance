# Conclusion to Object Inheritance

## Learning Goals

- Reduce repeated code and enhance objects using inheritance.
- Accomplish complex programming tasks using knowledge from previous modules.

***

## Key Vocab

- **Inheritance**: a tool that allows us to recycle code by creating a class
that "inherits" the attributes and methods of a parent class.
- **Composition**: a tool that enables you to recycle code by adding objects to
other objects. Rather than building on a base class as in inheritance,
composition leverages the attributes and methods of an instance of another class.
- **Subclass**: a class that inherits from another class. Colloquially called
a "child" class.
- **Superclass**: a class that is inherited by another class. Colloquially
called a "parent" class.
- **Child**: another name for a subclass.
- **Parent**: another name for a superclass.
- **`super()`**: a built-in Python function that allows us to manipulate the
attributes and methods of a superclass from the body of its subclass.
- **Decorator**: syntax that allows us to add functionality to an object
without modifying its structure.

***

## Conclusion

Inheritance is a common concept in our everyday lives, and, over the last
several lessons, we saw how Python implements it: by creating a family of
classes with shared behavior while still differentiating those classes. Because
of inheritance, we can define basic Python classes with large reusability,
along with smaller subclasses for more detailed behaviors. We can also take
advantage of inheritance by coding multiple, non-repetitive methods that cut
down on the total amount of code needed while also cleaning and optimizing the
code we do need. We also looked at how we can use the `super()` function to
inherit from and extend methods in the parent class. Finally, we took a closer
look at Python functions and learned how to avoid repeated code in our
functions with decorators.

You'll encounter inheritance in nearly every program you write.

***

## Resources

- [Python 3.8 Documentation](https://docs.python.org/3.8/)
- [Inheritance - Python](https://docs.python.org/3/tutorial/classes.html#inheritance)
- [PEP 318 - Decorators for Functions and Methods](https://peps.python.org/pep-0318/)
- [Inheritance and Composition: A Python OOP Guide - Real Python](https://realpython.com/inheritance-composition-python/)
- [Decorators in Python - GeeksforGeeks](https://www.geeksforgeeks.org/decorators-in-python/)
- [Supercharge Your Classes With Python super() - Real Python](https://realpython.com/python-super/)
