# Java ArithmeticException: Division by Zero

This repository demonstrates a common Java error: the `ArithmeticException` that occurs when dividing by zero. The `BuggyDivision.java` file contains code that causes this exception, while `FixedDivision.java` provides a solution.

## Problem
The `BuggyDivision.java` file attempts to divide an integer by zero, resulting in an `ArithmeticException` at runtime.

## Solution
The `FixedDivision.java` file demonstrates how to handle potential division-by-zero errors. It checks if the divisor is zero before performing the division. If the divisor is zero, it prints an error message or takes alternative actions rather than causing the program to crash.  Robust error handling is crucial for preventing unexpected program termination.