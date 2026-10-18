# Geometric Area Calculator

A simple geometric area calculator developed in Java to practice Object-Oriented Programming (OOP) concepts.

## About the Project

This application allows users to calculate the area of different geometric shapes through a console-based menu.

The project was created for learning purposes, focusing on Java fundamentals and object-oriented programming.

## Features

- Calculate the area of a square.
- Calculate the area of a rectangle.
- Calculate the area of a circle.
- Interactive console menu.
- Option to exit the application.

## Technologies

- Java
- Java Records
- Object-Oriented Programming (OOP)

## OOP Concepts

- **Interface:** `GeometricForm` defines the `getArea()` contract.
- **Polymorphism:** different geometric shapes are handled through the `GeometricForm` type.
- **Method overriding:** each shape implements its own `getArea()` method using `@Override`.
- **Records:** `Circle`, `Rectangle` and `Square` use records to represent their data.

## Project Structure

```text
geometric-area-calculator-java/
├── src/
│   ├── Main.java
│   ├── GeometricForm.java
│   ├── Circle.java
│   ├── Rectangle.java
│   └── Square.java
├── .gitignore
└── README.md
```

## Requirements

- Java 16 or later.
- An IDE such as IntelliJ IDEA, or a Java development environment configured on your machine.

## How to Run

1. Clone the repository:

   ```bash
git clone https://github.com/gabriels7cc/geometric-area-calculator-java.git
   ```

2. Open the project in IntelliJ IDEA.
3. Make sure the project SDK is configured for Java 16 or later.
4. Open `Main.java`.
5. Run the `main()` method.
6. Select a geometric shape from the menu and enter the requested measurements.

## Learning Goals

This project helped me practice interfaces, polymorphism, method overriding, records, and user input in Java.

---

Developed as part of my Java learning journey.