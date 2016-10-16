# C\# - Week 2

## Exercise *Fraction*
Define a class Fraction, which contains information about the rational fraction (e.g. 1/4). Define the appropriate fields, properties and constructors. Also define a property of type *decimal* to return the decimal value of the fraction (e.g. 0.25). Define a static method Parse() to create a fraction from a string. Write a function to cancel the fraction. (e.g. 10/15 is cancelled to 2/3).

## Exercise *Mobile*
1. We want to model the functionality of a mobile device. In the namespace *Mobile* implement a class which holds information about a mobile device: model, manufacturer, base price, features of battery (battery type and capacity) and features of the screen (resolution and pixel density). Implement each class and the data structures associated with it in a separate file. After instantiation, the information cannot change.
3. For each class, add some static methods which return an instance of known models.
4. Add a class Usage which holds information about the usage of the mobile device. This includes current percentage of battery,  OS information and call history. Each call record saves information about the date, time of start and time of end of the call and if it was incoming or outgoing. Provide useful properties like duration of the call.
5. Add methods to add/remove calls and also remove all.