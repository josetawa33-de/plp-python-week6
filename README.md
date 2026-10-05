# Week 6 Assignment - Safe Functions

- `safe_tools.py` - Contains three safe functions that handle division by zero, invalid numbers, and missing dictionary keys.
- `unbreakable.py` - Included as required by the assignment submission requirements.
- `README.md` - Describes the assignment files and explains why an if check cannot catch invalid text such as "abc".

An `if` check cannot catch `abc` when using `int("abc")` because converting the text to an integer raises a `ValueError`. The `try` and `except` block catches this error and prevents the program from crashing.