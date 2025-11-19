# 📐 Taylor Series Using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user.

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `x` and `n`
3. Get values for `x` and `n` from the user
4. Define a recursive function `series(x, n)`
   - **Base case:** If `n == 0`, return 1
   - **Recursive case:** Return `x**n / n + series(x, n-1)`
5. Print the result
6. **Stop**

## 💻 PROGRAM:
```
def series_sum(x, n):
    if n == 0:
        return 1
    else:
        return x**n + series_sum(x, n - 1)
try:
    x = int(input())
    n = int(input())
    result = series_sum(x, n)
    print(result)
except ValueError:
    print("Please enter valid integers for x and n.")
```
## OUTPUT
<img width="396" height="234" alt="image" src="https://github.com/user-attachments/assets/48514737-c648-41b0-9226-c516047b34d1" />

## RESULT
Thus the output is verified.

