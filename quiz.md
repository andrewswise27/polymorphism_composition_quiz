Polymorphism

What does the word 'polymorphism' mean?
Polymorphism means "many forms", and it occurs when we have many classes that are related to each other by inheritance. 

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
Polymorphism allows us to perform the same action in multiple ways. If you have classes of animals that inherit from an animal class, you could pass down a sound function that the classes could use in their own way.

What can we use to implement polymorphism in Java?
Inheritance

How many 'forms' can an object take when using polymorphism?
Many

Give an example of when you could use polymorphism.
When passing a general function down to classes that inherit from a parent class.



Composition and Aggregation

What do we mean by 'composition' in reference to object-oriented programming?
It describes a class that references one or more objects in an instance variable.

When would you use composition? Provide a simple example in Java.
Composition is when one or more classes are strongly coupled. For example if a house is composed of a roof, the roof cannot exist without the house.

Give a difference between composition and aggregation?
The difference between aggregation and composition is that aggregation is an association among two objects that have the “has a” relationship while the composition is a special type of aggregation that describes ownership.

What is/are the advantage(s) of using composition/aggregation?
There is principle, which sounds like "favor object composition over class inheritance". Composition over inheritance in OOP is the principle that classes should achieve polymorphism and code reuse by composition, instead of through inheritance.

When using composition, when an object is destroyed, what happens to all the objects it is composed of?
All of the objects it is composed of are also destroyed.

When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
Nothing, the parent class can exist without its children classes.