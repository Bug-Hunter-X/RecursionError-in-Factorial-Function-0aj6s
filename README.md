# RecursionError in Factorial Function

This repository demonstrates a common error in Python: the `RecursionError` that occurs when a recursive function lacks a proper base case to stop the recursion.  The example shows a factorial function that works correctly for non-negative inputs but crashes with a `RecursionError` for negative inputs.  The solution demonstrates how to add proper error handling for negative input.

## Bug

The `bug.py` file contains the buggy factorial function.  When called with a negative number, it causes a `RecursionError` because the recursion never stops.

## Solution

The `bugSolution.py` file demonstrates the solution. It includes a check for negative input and handles it gracefully, either by returning an error message or raising a ValueError.