# Week 6: Error Handling with try/except

This project implements safe_divide, safe_number, and get_field using 	ry/except blocks to handle runtime exceptions cleanly.

## Why if Checks Alone Are Not Enough

An if check alone cannot reliably catch invalid string conversions like "abc" without handling the ValueError raised by int(), because checking every possible invalid string format is error-prone and misses edge cases like whitespace, signs, or decimals. Similarly, checking keys or zero divisors manually across nested or dynamic inputs can still fail unexpectedly, whereas 	ry/except catches the exact runtime exception safely.
