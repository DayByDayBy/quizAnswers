 # Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Poly - many 
Morph - shape

Polymorphism is the ability to have many shapes, or present in more than one form



2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.


when a class can provide different implementations of a method depending on which object is passed - a car and a vehicle may both be able to move, for example 


3. What can we use to implement polymorphism in Java?

We can use overriding, or overloading


4. How many 'forms' can an object take when using polymorphism?

As many as necessary


5. Give an example of when you could use polymorphism.

When uncertain of which objects of a given class may need to be implemented, ie to leave room to scale




# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?


When a class is composed - on part or in whole - of other classes


7. When would you use composition? Provide a simple example in Java.


When various classes share attributes, especially when those attributes themselves could have attributes - a car may have an engine which itself may have cylinders, etc



8. Give a difference between composition and aggregation?

Composition is a subset of aggregation - a major difference between them is that composition implies that the one needs the other to exist, eg a dog has legs, whereas the other does not, eg the dog has a home



9. What is/are the advantage(s) of using composition/aggregation?

They are more flexible than inheritance, especially when scaling 



10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

They are also destroyed 

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

They remain, able to be used by other objects which use it 