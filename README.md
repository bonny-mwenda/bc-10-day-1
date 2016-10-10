# Bootcamp 10 Day 1 exercise

This is an illustration of OOP concepts. Two classes have been used as examples: Beverage and Alcohol

## Beverage Class
This is the base class. Takes two properties: name and volume of the beverage instance.
Methods:
  - drink - decrements volume of the beverage by the quantity passed
  - price - sets the price of the beverage based on volume

## Alcohol class
Inherits from Beverage class. Has the properties, name, volume, type and age.
Methods:
  - drink - uses the inherited method from beverage class to decrement volume when the beverage is drank
  - price - sets the price based on age of the drink
