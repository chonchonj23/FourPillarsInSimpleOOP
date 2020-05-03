# Four Pillars in OOP within Python

This is just a simple application of the four pillars of Object Oriented Programming within Python.


## 1. Abstraction: 
This code demo shows only one single aspect of wealth accumulation in a hypothetical family, and no other information is shown. 

## 2. Encapsulation: 
Family members' name, indiviudal savings, and family wealth are wrapped together into a unit, which, in our case, is either
Superclass (FamilyWealth) or Subclass (Father & Son).

## 3. Inheritance: 
In our code demo, the variables name, wealth & surname in Subclass (Father or Son) are inherited from Superclass (FamilyWealth).
Inheritance essentially allows a subclass to access the properties and behaviors of Superclass in an easy manner. 

## 4. Polymorphism: 
Polymorphism means "many forms".<br/> 
In our code demo, the wealth_check() function exists both in Superclass (FamilyWealth) and Subclass (Father or Son), 
but behaves differently depending on whether it is called from Superclass or Subclass, hence the "many forms" of wealth_check().

