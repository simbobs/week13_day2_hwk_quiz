# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

It means many forms.



2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

It means that we can wrap objects in an enclosing type that links the different object types. 
For example, if you had a network and wanted to connect to multiple object types(laptop, mobile, printer), rather than having so many different functions we can create an interface or use inheritance to make the objects of the same type. 



3. What can we use to implement polymorphism in Java?

Interfaces or Inheritance.

4. How many 'forms' can an object take when using polymorphism?

There is no limit. As many as you need. 

5. Give an example of when you could use polymorphism.

When you want to group classes together to make them the same type so that they can all exist within the one ArrayList.






# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

Composition is when an instance of an object is made up of instances of other objects. It is preferred over inheritance.

7. When would you use composition? Provide a simple example in Java.
When creaating an instance of house, it is composed of instances of roof, door, etc. 

8. Give a difference between composition and aggregation?

Composition is when an object is considered "a part of" whilst aggregation follows the rule of "has a". 
Composition means an object is owned by the object it is contained within whilst aggregation means the object can exist independently.

9. What is/are the advantage(s) of using composition/aggregation?
They allow a class to use behaviours from a group of other classes and means behaviours can change at run-time.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
they too are destroyed. 

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
They exist independently from the object so are not affected.