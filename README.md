# Reverse Polish Notation (RPN) Calculator

## Project Overview
This project is a terminal-based calculator that evaluates mathematical expressions written in **Reverse Polish Notation (RPN)**. It was developed as part of the **IC 2306 - Programming II** course. The application utilizes a **Stack data structure** to manage operands and perform arithmetic operations efficiently without the need for parentheses.

## Features
- **Stack-based Logic:** Implements fundamental data structure concepts (Push/Pop).
- **Operand Handling:** Supports floating-point numerical values.
- **Supported Operations:** Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`).
- **Precision:** Outputs results formatted to two decimal places.
- **Error Handling:** Includes checks for Stack Overflow, Stack Underflow, and Division by Zero.

## How to Use
The calculator uses specific instructions for input:
- `? [number]` : Pushes a number onto the stack.
- `+`, `-`, `*`, `/` : Performs the operation on the top two elements of the stack.
- `=` : Displays the current value at the top of the stack.
- `q` : Exits the program.

### Example
To calculate `(3 + 4) * (5 + 2)`, input the following:
`? 3 ? 4 + ? 5 ? 2 + * =`
**Output:** `Result: 49.00`

## Technologies Used
- **Language:** C
- **IDE:** Visual Studio / VS Code
- **Compiler:** GCC

## Authors
- **[Your Name]** - [Your Student Number]
- **[Partner's Name]** - [Partner's Student Number]
