# Java Swing Calculator

A desktop calculator written in Java with AWT and Swing. It uses a grid layout with custom colours and handles button clicks through event listeners.

## Features

- Addition, subtraction, multiplication and division
- Percentage, sign change (+/-) and square root
- Decimal input
- AC (clear) and = buttons
- Colour-coded operator and function buttons

## Technologies

Java, AWT, Swing.

## Project structure

```
src/
├── App.java          application entry point
└── Calculator.java   calculator window and logic
```

## Run

Requires JDK 8 or later.

```bash
javac -d bin src/*.java
java -cp bin App
```

## Known limitations

- No keyboard input; the calculator is used with the mouse.
- No automated tests.
