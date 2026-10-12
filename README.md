# Java OOP Lab Practical: Animal Hierarchy

## Overview
This project demonstrates core Object-Oriented Programming (OOP) concepts in Java through an Animal Hierarchy. It includes a parent class `Animal` and three child classes: `Dog`, `Cat`, and `Cow`.

## Concepts Covered
- **Inheritance:** Child classes extend the `Animal` parent class.
- **Method Overriding:** Each child class provides its own implementation of the `sound()` method.
- **Runtime Polymorphism:** Parent-class references are used to call child-class methods.
- **`super` Keyword:** Calls the parent constructor to initialize common properties.
- **Classes and Objects:** Represents real-world animals using Java classes and objects.

## Project Structure
```text
java-oop-inheritance-method-overriding/
├── Animal.java
├── Dog.java
├── Cat.java
├── Cow.java
├── Main.java
└── README.md
```

## Sample Output
```text
Dog
Name: Bruno
Age: 3 years
Sound: Woof! Woof!

Cat
Name: Whiskers
Age: 2 years
Sound: Meow! Meow!

Cow
Name: Gauri
Age: 5 years
Sound: Moo! Moo!
```

## Requirements
- Java 26 JDK
- IntelliJ IDEA or another Java-compatible IDE

## How to Run
1. Clone or download this repository.
2. Open the project in IntelliJ IDEA.
3. Ensure Java 26 is configured as the Project SDK.
4. Run `Main.java`.

**Note:** This project uses `IO.println()`, available through Java's simplified output API in Java 25 and later. Configure the project to support this API.

## Author
Rajesh Maurya

## Purpose
Created as part of a Java OOP Lab Session on Inheritance and Method Overriding.
