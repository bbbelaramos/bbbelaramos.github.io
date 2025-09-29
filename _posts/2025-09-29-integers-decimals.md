---
title: " 🔢 Int and float"
date: 2025-09-29 12:00:00 -03:00
categories: [Exercises]
tags: [Python,English]
---

## Problem Description:

You need to write a program that reads a decimal number and separates de integer part from the decimal part and shows in the format below:

```python
<inteiro> + <decimal>
```

Remember to show the the integer part as **int** and the decimal p0art as **float**.
The float part needs to have 2 decimals places max.

## Code
```python
number = float(input())

integer = number // 1

decimal = number % 1

print("%.0f" % integer,"+", "%.2f" % decimal)
```
## Input/Output

Ex.1: Input: 15.75, Output: 5 + 0.75

Ex.2: Input: 65, Output: 65 + 0.00

## Tips

&#8594; The symbol // stand for "floor division", it is just like a normal division but in the end it rounds to the smallest integer number.

For example: 7 / 2 -> 3.5
             7 // 2 -> 3

&#8594; That are other ways to make sure you have only 2 decimals places in the end.
```python
value = 2.1521
```
F-string:
 ```python
print(f"{value:.2f}")
```
.Format:
```python
print("{:.2f}".format(value))
```
