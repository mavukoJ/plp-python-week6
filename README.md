# Week 6 Assignment: Safe Functions

In this assignment, I practiced using `try` and `except` to handle errors in Python. I learned how to make my program continue running when it receives invalid input or encounters a problem.

## Files in this repository

- `safe_tools.py` — Contains three functions that handle division, convert text into numbers, and find information in a dictionary.
- `README.md` — Explains the assignment and what I learned about handling errors.

## Why can't an `if` check catch `abc` on its own?

An `if` statement can check a condition, but it does not automatically handle errors when Python tries to convert text into a number. I used `try` and `except ValueError` to handle text like `"abc"` and prevent the program from crashing.