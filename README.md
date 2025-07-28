# calculators-
ASSIGNMENT 1: Task1 and Task2



Task 1: 
Perform Basic Mathematical Operations
Problem Statement: Write a Python program that does the following:
1.  Takes two numbers as input from the user.
2.  Performs the basic mathematical operations on these two numbers:
o	Addition
o	Subtraction
o	Multiplication
o	Division
3.  Displays the results of each operation on the screen.

# Get input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Perform calculations
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2
division = num1 // num2

# Display the results
print("Addition:\n", addition)
print("Subtraction:", subtraction)
print("Multiplication:", multiplication)
print("Division:", division)


OUTPUT:-
Enter the first number: 5
Enter the second number: 10

Addition: 15.0
Subtraction: -5.0
Multiplication: 50.0
Division: 0.0


Task 2:
Create a Personalized Greeting
Problem Statement: Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.

   # 1. Takes a user's first and last name as input.
first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")

# 2. Concatenates the first name and last name into a full name.
f = first_name + " " + last_name

# 3. display the result.
print(f"Hello, {f}! Welcome to the  python program.")

output:
Enter your first name: suman
Enter your last name: kanti
Hello, suman kanti! Welcome to the  python program.
