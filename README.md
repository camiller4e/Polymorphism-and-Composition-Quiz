Polymorphism

Q. What does the word 'polymorphism' mean?
A. From the greek “polys” meaning ‘many’ and and “morphe” 	meaning ‘shape’. So: many shapes. 

Q. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
A. Polymorphism refers to a process whereby a class can fulfil more roles than those defined by only that class.
   For example: in our recent Car Dealership lab, we created various instances of a Vehicle class, and gave them all access to an Interface named “IWheels” which ensured that all instances of the vehicle class must have a number of wheels. Using an interface allowed us to create an ArrayList of all vehicles which utilised this interface.

Q. What can we use to implement polymorphism in Java?
A. We can use abstract classes(or superclasses) and interfaces. 

Q. How many 'forms' can an object take when using polymorphism?
A. If we use interfaces, there’s technically no limit to how many forms an object could take. 

Q. Give an example of when you could use polymorphism. 
A. You might use it in game design, say if you had a variety of different sprites. Each sprite class might have different functions but they  would all need to move around. An interface named IMove which promises a move function would allow you to act on all of these sprites despite  them being different classes.

Composition

Q. What do we mean by 'composition' in reference to object-oriented programming?
A. This is the process of making classes/objects whose properties are made up, either in part or completely, by other classes/objects.

Q. When would you use composition? Provide a simple example in Java.
A. Again, in the Car Dealership example we had a Component superclass which was extended by an Engine class and a Tyre class. We then had a   Vehicle superclass whose properties were an Engine and an array of Tyres. 

Q. What is/are the advantage(s) of using composition? 
A. It helps us keep our code dry and tidy by not cluttering the code up with long inheritance chains and without using too many interfaces.

Q. What happens to the behaviours when the object composed of them is destroyed?
A. They are also destroyed. 
