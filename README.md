

# Expression Calculator

This project is a simple Expression Calculator implemented in C++. It allows users to evaluate arithmetic expressions with support for parentheses and operator precedence through a menu-driven interface.

## Features

- Accepts arithmetic expressions with `+`, `-`, `*`, `/`
- Handles parentheses and operator precedence
- Converts infix expressions to postfix (Reverse Polish Notation)
- Evaluates the postfix expression using a stack
- User-friendly interface; type `exit` to quit

## Project Structure

```
expression-calculator
├── src
│   └── main.cpp        # Entry point and calculator logic
├── Makefile            # Build rules for compiling the project
└── README.md           # Documentation for the project
```

## Building the Project

To build the project, navigate to the project directory and run the following command:

```
make
```

Or, compile manually:

```
g++ src/main.cpp -o expression-calculator
```

## Running the Application

After building the project, you can run the application using the following command:

```
./expression-calculator
```

## Sample Output

```
Expression Calculator
Enter an arithmetic expression (or 'exit' to quit): (3 + 5) * 2
Result: 16

Enter an arithmetic expression (or 'exit' to quit): 10 + 6 / 2
Result: 13

Enter an arithmetic expression (or 'exit' to quit): (8 + 2) * (5 - 3) / 2
Result: 10

Enter an arithmetic expression (or 'exit' to quit): (5 + (3 * 2))
Result: 11
```

## License

This project is open-source and available for modification and distribution.
