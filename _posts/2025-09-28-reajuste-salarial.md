---
title: " 💵 Salary adjustment"
date: 2025-09-28 19:00:00 -03:00
categories: [Exercises]
tags: [Python,English]
---

## Problem Description:

You need to write a program that calculates a salary adjustment based on the rules below:

&#8594; Employees that receive up to $2500,00 get a 20% increase in their salary.

&#8594; Employees that receive more than $2500,00 get a 15% increase in their salary.

The program should start reading the current salary and print the new one with two decimals places.

## Code

```python
salary = float(input())

if salary <= 2500:
    new_salary = salary * 1.2
else:
    new_salary = salary * 1.15

print("%.2f" % new_salary)

```
