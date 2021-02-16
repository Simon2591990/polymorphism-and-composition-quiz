# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

When an Object can be treated as more than one object type

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

We apply polymorphism when we use an treat an object as a type other than its Class Name

3. What can we use to implement polymorphism in Java?

Inheretance or Interfaces

4. How many 'forms' can an object take when using polymorphism?

2147483647

5. Give an example of when you could use polymorphism.

A Car could be treated as a Car or a Vehicle using polymorphism.
This would allow Car to have all the same functionallity as an abstract vehicle but without repeating all of the methods and properties within Vehicle.



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

Composition means using pre build objects in the constructor of another object

7. When would you use composition? Provide a simple example in Java.

A Car could have a composition that includes an Engine object

8. Give a difference between composition and aggregation?

Composition uses items that are pre built and can be independent.
Aggregation builds new objects when the Object is created

9. What is/are the advantage(s) of using composition/aggregation?

Composition is more flexible than Aggregation



10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

the composition objects still exist independently 

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

The aggregated objects are also destroyed