# 12_Exceptions

1).
This code defines a class Counter with several methods for managing a numerical counter. The __init__ method initializes the current value of the counter, as well as the minimum and maximum values it can take. The set_current, set_max, and set_min methods allow the user to change the current, maximum, and minimum values of the counter, respectively. The step_up and step_down methods increase and decrease the current value of the counter by 1, respectively. The get_current method prints the current value of the counter to the console.

2).
This code defines three classes: Human, Student, and Group. Human is a superclass that contains attributes for a person's gender, first name, last name, and age, as well as a __str__ method that returns a string representation of the object. Student is a subclass of Human that adds an attribute for a record book, and overrides the __str__ method of the Human class to only return the record book attribute. Group is a class that contains a set of Student objects and methods for adding, deleting, and finding students within the group. It also overrides the __str__ method to return a formatted string representation of all the students in the group.

3).
This code defines a class Rectangle with attributes for the width and height of a rectangle. The __init__ method checks that the width and height are both numbers, and raises a ValueError if either is not. The __str__ method returns a string representation of the object, including the width and height attributes.

4).
This code defines a class Temperature with an attribute for a temperature in Celsius. The __init__ method checks that the temperature is a number, and raises a TypeError if it is not. The class also has two methods, to_fahrenheit and to_kelvin, which convert the temperature to Fahrenheit and Kelvin, respectively, and return a string representation of the converted temperature.

5).
This code defines a class User with attributes for a user's name and age. The __init__ method checks that the name is a string and the age is a number, and raises a ValueError if either is not. The class also has two methods, test_name and test_age, which return a string representation of the user's name and age, respectively.

6).
This code defines a class BankAccount with attributes for a balance and an owner. The withdraw method allows the user to withdraw a certain amount of money from the account, and raises a TypeError if the amount is not a number or a ValueError if the amount is greater than the account balance. The method then subtracts the withdrawn amount from the account balance and returns the new balance.
