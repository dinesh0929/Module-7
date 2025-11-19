# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
```
def fun(n):
    if (n > 0):
        fun(n - 1)
        print(n, end=" ")
 

x = int(input())
fun(x)
```

## OUTPUT

<img width="1087" height="271" alt="image" src="https://github.com/user-attachments/assets/a32478fc-e2b8-456f-8a11-4ef8b41dd2a8" />

## RESULT
Thus a Python program to find the sum of square of a first n Natural Numbers using recursion is verfied.

