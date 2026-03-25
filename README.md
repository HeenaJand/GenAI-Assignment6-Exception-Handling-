# GenAI-Assignment6-Exception-Handling-

Python Exception Handling Tasks

Overview

This project demonstrates the use of exception handling in Python through multiple practical tasks. It covers handling common runtime errors, creating custom exceptions, working with files safely, and building a small interactive program.

---

Task 1: Safe Division Utility

Description

A program that takes two numbers as input and performs division safely.

Concepts Used

- "try", "except", "else", "finally"
- Handling:
  - "ValueError" (invalid input)
  - "ZeroDivisionError" (division by zero)

Outcome

- Prevents crashes due to invalid input
- Always prints completion message

---

Task 2: Bill Calculator with Error Handling

Description

Processes a list of item prices and calculates total while handling invalid data.

Concepts Used

- Looping through list
- Custom error raising using "raise"
- Handling:
  - "TypeError" (non-numeric values)
  - "ValueError" (negative prices)

Key Feature

- Uses "ValueError as e" to display custom error messages

Example

- Skips invalid entries like "'abc'"
- Rejects negative values like "-200"
- Continues calculation without stopping program

---

Task 3: Custom Exception (Age Validator)

Description

Validates user age input using a custom condition.

Concepts Used

- Custom exception using "raise ValueError"
- Input validation

Condition

- Age must be between 1 and 120

Outcome

- Displays error for invalid age
- Accepts valid input

---

Task 4: File Reader with Exception Handling

Description

Reads the first 3 lines of a file safely.

Concepts Used

- File handling ("open")
- Exception handling:
  - "FileNotFoundError"
  - "PermissionError"
- "finally" block for guaranteed execution

Important Note

- File is searched in the Current Working Directory (CWD) by default

---

Task 5: Mini Program (Safe Shopping Cart)

Description

Interactive program to input item prices and calculate total bill.

Features

- Accepts multiple inputs
- Stops when user enters "'q'"
- Validates:
  - Non-numeric input
  - Negative values

Concepts Used

- Loops
- Exception handling
- List operations
---

How to Run These Files

Option 1: Using Jupyter Notebook

1. Open Jupyter Notebook
2. Create a new notebook or open existing ".ipynb" file
3. Copy each task code into separate cells
4. Run each cell using:
   - Run button OR
   - "Shift + Enter"

Make sure:

- Your file (for Task 4) is in the same folder as the notebook

---

Option 2: Using Python File (.py)

1. Open any editor (VS Code / PyCharm / Notepad)
2. Create a file:
   tasks.py
3. Paste all code into the file
4. Open terminal in that folder
5. Run:
   python tasks.py

---

Important (File Handling - Task 4)

- Place your file (e.g., "data.txt") in the same folder as your script
  OR
- Provide correct path:
  open("files/data.txt", "r")

---
