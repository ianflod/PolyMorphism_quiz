# PolyMorphism_quiz

**Q1. What does the word Polymorphism mean**

A1. It is a greek word meaning many shaped.

**Q2. What does it mean when we apply Polymorphism to OO design?  Give a Java example**

A2. It means we can write code that will perform differently in different scenarios.  We can have create a function in a super class and pass it to subclasses where it will perform a slightly different action in each e.g. render a square, circle, pentagon etc.

**Q3. What can we use to implement Polymorphism in Java?**

A3. Polymorphism can be implemented using both inheritance and interfaces in Java.

**Q4 How many forms can an object take when using Polymorphism?**

A4. As many as are required.

**Q5 Give an example of when you could use polymorphism?**

A5. We could have a Vehicle superclass which has subclasses of plane, car and motorbike. A method called vehicle sound could be created which would return a different string for each class along the lines of "Vehicle noise", "Whhooosh", "Broom broom", "Vrrooom"

**Q6. What do we mean by 'composition in reference to OOP?**

A6. In composition we see an object as being part of another object. 

**Q7. When would you use composition?  Provide a simple example.**

A7. We use it to compose objects from other objects to get the functionality we need. e.g. within a car class we could have an engine class and a gearbox class.

**Q8 Give a difference between Aggregation and Composition**

A8. In aggregation an object can exist in its own right and away from the object which contains it.  This is not the case for composition.  If the car is destroyed the engine is destroyed also.

**Q9 Advantages of composition/aggregation?**

A9.  Re-usable code.  An object can have a method which is utilised by many other objects.
     There is no conflict between method property names.
    
    
 **Q10 In composition when an object is desroyed, what happens to the objects it is composed of?**
 
 A10. They are also destroyed
 
 **Q11 In aggregation, when an object is destroyed, what happens to the objects it is composed of?**
 
 A11.  They can live on. Aggregation objects can exist independently of the object which it composes.
