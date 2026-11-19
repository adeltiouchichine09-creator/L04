# Bug reports for exercise2.py

Line: 1
Problem: The docstring says "True if the grade is 5 or more", which means grade >= 5, but the function returns grade > 5, which excludes 5. This is a boundary condition error.
Example: is_passing(5) -> False, expected True
Fix: return grade >= 5

Line: 6
Problem: The docstring says "At least 8 characters", which means length >= 8, but the function uses len(password) > 8, which excludes 8. This is a boundary condition error.
Example: is_valid_password("12345678") -> False, expected True
Fix: return len(password) >= 8 and any(c.isdigit() for c in password)

Line: 11
Problem: The function incorrectly uses max(low, min(x, low)), which simplifies to low regardless of x. It should be max(low, min(x, high)).
Example: clamp(3, 1, 5) -> 1, expected 3
Fix: return max(low, min(x, high))
