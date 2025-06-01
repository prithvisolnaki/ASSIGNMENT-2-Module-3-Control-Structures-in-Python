# ASSIGNMENT-2-Module-3-Control-Structures-in-Python
ASSIGNMENT 2:
 Task 1: Check if a Number is Even or Odd

## 🧾 Problem Statement

Write a Python program that:

1. Takes an integer input from the user.
2. Checks whether the number is even or odd using an if-else statement.
3. Displays the result accordingly.

**Sol:**

# Taking input from the user and converting it to integer
number = int(input("Enter a number: "))

# Checking whether the number is even or odd
if number % 2 == 0:
    print(str(number) + " is an Even Number")
else:
    print(str(number) + " is an Odd Number")

**Output:**
Enter a number: 7
7 is an Odd Number
Enter a number: 8
8 is an Even Number

**Task 2: Sum of Integers from 1 to 50 Using a Loop**
 
Problem Statement: Write a Python program that:
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.

**Sol:**

sum = 0
for i in range(1, 51):
    sum = sum + i
print("The sum of numbers from 1 to 50 is:", sum)

**Output:**
The sum of numbers from 1 to 50 is: 1275
