# Assignment-2
# Even or Odd Number Checker

This Python program checks whether the number entered by the user is **even** or **odd**.

## 📋 Program Explanation
1. The user is asked to enter a number.
2. The program checks the remainder when the number is divided by 2:
   - If `num % 2 == 0` → the number is **even**.
   - Otherwise → the number is **odd**.
3. The result is displayed on the screen.

## 💻 Code
```python
num = int(input("Enter the number: "))
if num % 2 == 0:
    print(num, "is an even number")
else:
    print(num, "is an odd number")
```
Output
```
Enter the number: 12
12 is an even number
csharp
Copy
Edit
Enter the number: 9
9 is an odd number
```


# Sum of Numbers from 1 to 50

This Python program calculates the sum of numbers from **1 to 50** using a `for` loop.

## 📋 Program Explanation
1. A variable `sum` is initialized to 0.
2. A `for` loop runs from 1 to 50 (inclusive).
3. On each iteration, the current number is added to `sum`.
4. The running total is printed.

⚠️ **Note**: Since the `print()` statement is inside the loop, it prints the sum after **each addition**, not just the final result.

## 💻 Code
```python
sum = 0
for i in range(1, 51):
    sum += i
    print("the sum of numbers from 1 to 50:", sum)
```
Output
```
the sum of numbers from 1 to 50: 1
the sum of numbers from 1 to 50: 3
the sum of numbers from 1 to 50: 6
...
the sum of numbers from 1 to 50: 1275
```

