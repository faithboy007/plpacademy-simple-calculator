# Simple Python Calculator

A command-line calculator that performs basic arithmetic operations based on user input.

## Features

- Performs four basic operations:
  - Addition (+)
  - Subtraction (-)
  - Multiplication (*)
  - Division (/)
- Handles decimal numbers
- Includes error handling for:
  - Invalid number inputs
  - Division by zero
  - Invalid operations
- Clear output showing the full calculation

## Requirements

- Python 3.x

## Installation

No installation required. Simply download or copy the script to your local machine.

## Usage

1. Run the script:
   ```bash
   python calculator.py
Follow the prompts:

Enter the first number

Enter the second number

Choose an operation (+, -, *, /)

View the result in the format: num1 operation num2 = result

Example
text
Simple Calculator
Available operations: + (addition), - (subtraction), * (multiplication), / (division)
Enter the first number: 10
Enter the second number: 5
Enter the operation (+, -, *, /): +
10.0 + 5.0 = 15.0
Error Handling
The program handles several error cases:

Non-numeric inputs: Error: Please enter valid numbers!

Division by zero: Error: Division by zero is not allowed!

Invalid operations: Invalid operation! Please use one of: +, -, *, /

Code Structure
Main calculator() function containing all logic

Input collection with input() and float() conversion

Operation handling with if/elif statements

Formatted output using f-strings

Comprehensive exception handling

Possible Extensions
Add more operations (%, **, etc.)

Implement continuous calculation mode

Add calculation history

Create a GUI version

Add unit tests




