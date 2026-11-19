# Bug reports for exercise1.py

Line: 3
Problem: The condition `n % 2 == 1` checks if a number is odd, not even. For even numbers, the remainder when divided by 2 should be 0, not 1. The function should return `True` when `n % 2 == 0`.
Example: Input: 4, actual result: False, expected result: True
Fix: return n % 2 == 0

Line: 8
Problem: The function calculates the sum of width and height, not the area of a rectangle. The area should be width multiplied by height.
Example: Input: width=5, height=3, actual result: 8, expected result: 15
Fix: return width * height

Line: 13
Problem: The function adds 2 to the number instead of doubling it. To double a number, it should multiply it by 2.
Example: Input: 5, actual result: 7, expected result: 10
Fix: return n * 2
