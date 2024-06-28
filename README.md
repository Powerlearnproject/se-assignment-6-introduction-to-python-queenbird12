[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15306482&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a high-level, interpreted programming language known for its readability, simplicity, and versatility. Key features include:

Readability: Simple and clean syntax.
Versatility: Used in web development, data analysis, artificial intelligence, scientific computing, automation, and more.
Extensive Libraries: Rich standard library and a vast ecosystem of third-party packages.
Community Support: Large, active community.
Examples of use cases:

Web Development: Using frameworks like Django and Flask.
Data Analysis and Visualization: Using libraries like Pandas, NumPy, and Matplotlib.
Machine Learning and AI: Using libraries like TensorFlow and scikit-learn.
Automation/Scripting: Writing scripts to automate repetitive tasks.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

Go to the Python downloads page.
Download the installer for Windows.
Run the installer and check "Add Python to PATH".
Click "Install Now".
 pip install virtualenv
python -m venv myenv
myenv\Scripts\activate


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

print("Hello, World!")
print: Built-in function to output text.
"Hello, World!": String literal enclosed in double quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

int: Integer numbers.
float: Floating-point numbers.
str: Strings, text data.
bool: Boolean values, True or False.
list: Ordered, mutable collection.

age = 25
print(age)
height = 5.9
print(height)
name = "Alice"
print(name)
is_student = True
print(is_student)
fruits = ["apple", "banana", "cherry"]
print(fruits)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

conditional statements are used execute blocks of code based on specific conditional.

age = 18
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")

fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

Functions are reusable blocks of code that perform a specific task. They help in organizing code and reducing redundancy.

def add_numbers(a, b):
    return a + b

result = add_numbers(3, 5)
print(result)


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

List: Ordered, mutable collection of items. Indexed by position.
Dictionary: Unordered, mutable collection of key-value pairs. Indexed by keys.

# List of numbers
numbers = [1, 2, 3, 4, 5]
print(numbers)

# Dictionary with key-value pairs
person = {"name": "Alice", "age": 25, "city": "New York"}
print(person)

# Basic operations
# List
numbers.append(6)
print(numbers)

# Dictionary
person["email"] = "alice@example.com"
print(person)

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

Exception handling allows you to manage and respond to errors in a controlled way using try, except, and finally blocks.
try:
    result = 10 / 0
except ZeroDivisionError as e:
    print(f"Error occurred: {e}")
finally:
    print("This will always execute.")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

Module: A single Python file containing code (functions, classes, etc.).
Package: A collection of modules organized in directories

import math

# Using the math module
result = math.sqrt(16)
print(result)

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

reading files
with open('example.txt', 'r') as file:
content = file.read()
print(content)

writing file
lines = ["Hello, World!", "This is a test file.", "Goodbye!"]
with open('example.txt', 'w') as file:
    for line in lines:
        file.write(line + '\n')

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


