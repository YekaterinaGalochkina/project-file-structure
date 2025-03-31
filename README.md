Math Operations Module

Overview

This module provides basic arithmetic operations including addition, subtraction, multiplication, and division. Each operation is implemented as a function called perform_operation with different parameter signatures.

Functions

1. Addition

perform_operation(augend, addend)

Description: Returns the sum of two numbers.
Parameters:
augend (int/float): The first number.
addend (int/float): The second number.
Returns: The sum of augend and addend.

2. Subtraction

perform_operation(minuend, subtrahend)

Description: Returns the difference between two numbers.
Parameters:
minuend (int/float): The number from which another number is subtracted.
subtrahend (int/float): The number to subtract.
Returns: The difference of minuend and subtrahend.

3. Multiplication

perform_operation(multiplier, multiplicand)

Description: Returns the product of two numbers using repeated addition.
Parameters:
multiplier (int): The number of times multiplicand is added.
multiplicand (int/float): The number to be multiplied.
Returns: The product of multiplier and multiplicand.

4. Division

perform_operation(dividend, divisor)

Description: Returns the quotient of division. Raises an error if division by zero is attempted.
Parameters:
dividend (int/float): The number to be divided.
divisor (int/float): The number by which division occurs.
Returns: The quotient of dividend divided by divisor.
Raises: ValueError if divisor is zero.


Testing

We have tests for every function. To run the tests, use the following command:
pytest test_X.py
Replace X with addition, subtraction, multiplication, or division.
If the file you are testing is nested in a sub-directory, please remember to cd into the directory before running the command.


License

This project is licensed under the MIT License.

