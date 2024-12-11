# Python Bug: ZeroDivisionError in Average Calculation

This repository demonstrates a common error in Python: the `ZeroDivisionError` that can occur when calculating the average of an empty list.

The `bug.py` file contains code that attempts to calculate the average of a list of numbers. However, it does not handle the case where the input list is empty, resulting in a division by zero error.

The `bugSolution.py` file provides a corrected version of the code. The solution handles empty lists gracefully, preventing the `ZeroDivisionError`.