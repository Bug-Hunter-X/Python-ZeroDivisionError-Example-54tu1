# Python ZeroDivisionError Example

This repository demonstrates a common Python error: ZeroDivisionError.  It shows how to handle this error using try-except blocks.

## The Bug (bug.py)

The `my_function` attempts to divide `a` by `b`, but if `b` is 0, it leads to a `ZeroDivisionError`. 

## The Solution (bugSolution.py)

The solution involves using a `try-except` block to catch and handle the `ZeroDivisionError`. If the error occurs, a user-friendly message is printed instead of the program crashing.