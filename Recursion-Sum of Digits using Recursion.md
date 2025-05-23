# #  Recursion:Sum of Digits using Recursion in Python

##  AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

##  ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

##  PROGRAM:

```python

def sum_digit(n):
    return 0 if n <= 0 else n % 10 + sum_digit(n // 10)

n = int(input())
print(sum_digit(n) if n >= 0 else "Enter valid number")


```

## OUTPUT

![image](https://github.com/user-attachments/assets/fe059b09-d655-4f62-a61f-f29e904db6eb)

## RESULT

Thus, the program has been successfully executed.
