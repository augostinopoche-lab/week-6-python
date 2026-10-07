# PLP Python Week 6 - Safe Functions

## Files

* `safe_tools.py` - Contains three safe functions that handle division by zero, invalid number input, and missing dictionary keys.
* `README.md` - Contains the assignment information and explanation of error handling.

## Why can the `if` check not catch `abc` on its own?

An `if` check cannot catch `abc` when using `int()` because `int("abc")` raises a `ValueError` during the conversion. The `try`/`except` block catches this error and returns `Not a number` instead of allowing the program to crash.
