# Homework13
These are my solutions for Homework 13

Task 1 - Kitchen Appliance Simulation
In this project, you will apply the principles of Object-Oriented Programming (OOP) to
create a simulation of various kitchen appliances. This task involves defining a hierarchy
of classes that models different types of kitchen devices, including a coffee machine, a
blender, and a meat grinder. The core objective is to practice inheritance, one of the
fundamental concepts of OOP, while also considering other OOP principles such as
encapsulation.
Objectives:
1. Design the Base Class - Device:
Create a class named Device that will serve as the base class for all kitchen devices.
This class should define common attributes that all devices share, such as name, model,
and power_consumption. Implement common methods that could be used by any
device, such as turn_on() and turn_off(). These methods might simply print a message
indicating that the device has been turned on or off.
2. Implement Derived Classes for Specific Devices:
● CoffeeMachine: Create a class named CoffeeMachine, inheriting from Device. This
class should include attributes specific to a coffee machine (e.g., coffee_type) and
implement additional methods such as brew_coffee(), which simulates the action of
brewing coffee. This method might simply print a message.
● Blender: Create a class named Blender, inheriting from Device. This class should have
attributes unique to a blender (e.g., blade_speed) and include a method blend(),
simulating the blending action. This method might simply print a message.
● MeatGrinder: Develop a class named MeatGrinder, inheriting from Device. It should
contain attributes specific to a meat grinder (e.g., grind_size) and implement a method
grind_meat(), representing the meat grinding process. This method might simply print a
message.


Task 2 - Passport Management System
1. Implement the Passport Class:
● The Passport class should encapsulate the essential attributes of a passport, such as
the passport holder's name, date of birth, passport number, and country of
citizenship.
● Include methods that allow for setting and retrieving these attributes, and a method for
printing the passport's details in a readable format.
2. Create the ForeignPassport Class through Inheritance:
● Derive the ForeignPassport class from the Passport class. This subclass should
inherit the attributes and methods of the Passport class and introduce additional
properties specific to a foreign passport. These might include:
● A list of visas (each visa can be a simple string).
● A unique foreign passport number (distinct from the standard passport number).
● Implement methods to manage the foreign passport's additional data, such as adding a
visa and printing the complete foreign passport details, including all visas.
