# Unhandled Division and Modulo by Zero Errors

This repository demonstrates a common coding error in JavaScript:  unhandled division and modulo by zero.  The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version with improved error handling.

## Bug Description

The original code performs basic arithmetic operations (addition, subtraction, multiplication, division, modulo). However, it fails to gracefully handle cases where division or modulo operations involve a zero divisor, leading to runtime errors.

## Solution

The solution involves adding more robust error checks to prevent the program from crashing when dividing or taking the modulo of zero.  Specifically, the improved code checks for zero divisors *before* performing the operation, thus preventing exceptions.