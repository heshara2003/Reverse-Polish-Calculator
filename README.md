# IC 2306 - Programming II: Reverse Polish Calculator

## Institutional Information
* [cite_start]**University:** University of Colombo [cite: 1]
* [cite_start]**Faculty:** Faculty of Technology [cite: 2]
* [cite_start]**Course:** IC 2306 - Programming II [cite: 2]

## Student Details
* **Name:** P.H.H.S. JAYASINGHE
* **Student Number:** 2023t01866

---

## Project Overview
[cite_start]This project implements a **Reverse Polish Notation (RPN) Calculator** using the **C programming language**[cite: 60]. [cite_start]The core of this application is built upon the **Stack Data Structure**, which allows for the evaluation of mathematical expressions without the need for parentheses[cite: 51, 59]. 

[cite_start]This project was developed to satisfy the requirements of the Programming II final group project[cite: 1, 39].

## Features
- [cite_start]**Stack-Based Logic:** Operands are pushed onto a stack, and operations pop them to compute and push results back[cite: 51, 52].
- [cite_start]**RPN Evaluation:** Supports postfix notation where operators follow their operands[cite: 42].
- [cite_start]**Robust Arithmetic:** Supports Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`)[cite: 54].
- **Precise Output:** Results are displayed formatted to two decimal places.
- **Visual Studio Compatible:** Optimized to run without security warnings (`_CRT_SECURE_NO_WARNINGS`).

## How the Calculator Works
[cite_start]The program processes specific character instructions as follows[cite: 53, 54, 55]:
- `? [value]` : Reads a numerical value and pushes it onto the stack.
- `+ , - , * , /` : Performs the respective arithmetic operation.
- `=` : Prints the current value at the top of the stack without popping it.
- `q` : Terminates the program.

### Calculation Example
To evaluate $(3.14 + 7) * 2$:
**Input:** `? 3.14 ? 7 + ? 2 * =`
**Output:** `Result: 20.28`

## Technical Implementation
- [cite_start]**Data Structure:** Static Array-based Stack[cite: 60].
- [cite_start]**Algorithm:** Postfix expression evaluation algorithm[cite: 42, 51].
- [cite_start]**Environment:** Developed and tested using Visual Studio / VS Code[cite: 61].

## Submission Requirements
- [x] [cite_start]Correct C Source Code [cite: 6, 8]
- [x] [cite_start]Public GitHub Repository 
- [x] [cite_start]Project Report (Methodology, Screenshots, Discussion) [cite: 5, 10, 13]
- [x] [cite_start]Recorded Presentation (Maximum 15 minutes) [cite: 20, 31]

---
© 2026 P.H.H.S. JAYASINGHE | University of Colombo
