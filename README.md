# 🐍 Python Programs

This repository contains two simple Python programs:

1. ✅ Even or Odd Number Checker  
2. ➕ Sum of Numbers from 1 to 50

---

## 1️⃣ Program: Even or Odd Number Checker

### 📄 Description:
This program takes a user input number and determines whether the number is **even** or **odd**.

### 💻 Code:
```python
n = int(input('Enter a number: '))
if n % 2 == 0:
    print(n, 'is an even number')
elif n == 1:
    print(n, 'is an odd number')
else:
    print(n, 'is an odd number')

# ➕ Sum of Numbers from 1 to 50
# ➕ Python Program: Sum of Numbers from 1 to 50

## 📄 Description
This Python program uses a `for` loop to iterate over numbers from **1 to 50** and calculates the **sum of all these integers**. It's a simple example of loop-based summation, commonly used in beginner-level Python practice.

---

## 💻 Code

```python
sum = 0
for i in range(1, 51):
    sum += i
print("The sum of numbers from 1 to 50 is:", sum)
