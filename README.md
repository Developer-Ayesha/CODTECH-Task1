# CODTECH-Task1
NAME:-Ayesha Sajid Khan
COMPAANNY:-CODTECH IT SOLUTIONS
ID:-CT4PP4789
DOMAIN:-Python Programming
DURATION:-JULY 15th to AUGUST 15th
MENTOR:-

OVERVIEW OF THE PROJECT
Certainly! The provided Python code defines a simple command-line calculator with basic arithmetic operations. Here's an overview of each component:

### Function Definitions:
1. **add(x, y)**:
   - Parameters: `x` and `y` (numbers)
   - Purpose: Returns the sum of `x` and `y`.

2. **subtract(x, y)**:
   - Parameters: `x` and `y` (numbers)
   - Purpose: Returns the result of `x - y`.

3. **multiply(x, y)**:
   - Parameters: `x` and `y` (numbers)
   - Purpose: Returns the product of `x` and `y`.

4. **divide(x, y)**:
   - Parameters: `x` and `y` (numbers)
   - Purpose: Returns the result of `x / y`.
   - Handles division by zero error by checking if `y` is zero.

5. **floordiv(x, y)**:
   - Parameters: `x` and `y` (numbers)
   - Purpose: Returns the floor division result of `x // y`.

6. **exponential(x, y)**:
   - Parameters: `x` and `y` (numbers)
   - Purpose: Returns `x` raised to the power of `y` (`x ** y`).

7. **modulus(x, y)**:
   - Parameters: `x` and `y` (numbers)
   - Purpose: Returns the remainder of `x` divided by `y` (`x % y`).

### Calculator Function (`calculator()`):
- Purpose: Provides a menu-driven interface to perform arithmetic operations based on user input.

1. **Menu Display**:
   - Prints options for addition, subtraction, multiplication, division, floor division, exponential, and modulus.

2. **User Input**:
   - Prompts the user to choose an operation (`1` to `7`) and enter two numbers (`num1` and `num2`).

3. **Operation Execution**:
   - Based on the user's choice:
     - Calls the corresponding function (`add`, `subtract`, etc.) with `num1` and `num2`.
     - Prints the result of the operation.

4. **Error Handling**:
   - Checks if the user's choice is valid (`1` to `7`). If not, it informs the user with an error message.

### Example Interaction:
- User selects operation `3` (multiplication), enters `5` and `3` as numbers:
  ```
  1. Addition
  2. Subtraction
  3. Multiplication
  4. Division
  5. Floor Division
  6. Exponential
  7. Modulus
  Enter your choice (1/2/3/4/5/6/7): 3
  Enter first number: 5
  Enter second number: 3
  Multiplication of 5.0 and 3.0 is: 15.0
  ```


