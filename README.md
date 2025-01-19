# Uncommon Python Bug: Stack Overflow in Recursive Factorial Function

This repository demonstrates a common yet often overlooked bug in recursive functions: the lack of handling for negative input values in the factorial function.  The recursive implementation leads to infinite recursion and ultimately a stack overflow error when a negative number is provided as input.

The `bug.py` file contains the buggy code, whereas `bugSolution.py` provides a corrected version.