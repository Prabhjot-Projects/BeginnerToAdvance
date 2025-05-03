
# Day 2: Python Basics — Variables, Data Types, Input/Output, and Functions

---

## 🎯 Learning Objectives

By the end of this lesson, you will be able to:

- Understand what variables are and how to use them.
- Identify and use common Python data types.
- Use input and output functions to interact with the user.
- Define and call simple functions in Python.

---

## 1. Variables

### Definition

A **variable** is a symbolic name that stores data in a computer’s memory. It allows you to label and manipulate data throughout your program.

Python variables are dynamically typed, meaning you don’t need to declare the type explicitly; it is inferred from the assigned value.

### Example

```python
age = 25               # integer
name = "Prab"          # string
height = 5.9           # float
is_student = True      # boolean

```

### Task

- Create variables to store your name, age, height, and student status.
- Print the values of all these variables.

---

**Resource for further reading on variables:**

[W3Schools - Python Variables](https://www.w3schools.com/python/python_variables.asp) — simple and beginner-friendly.

---

## 2. Data Types

### Definition

**Data types** specify the kind of data a variable holds. Python’s common built-in types include:

- `int` — integers (whole numbers)
- `float` — decimal numbers
- `str` — text strings
- `bool` — Boolean values (`True` or `False`)
- `list` — ordered collection of items
- `dict` — key-value pairs

Knowing data types helps you perform the right operations and understand data behaviour.

### Example

```python
num = 10                  # int
pi = 3.1415               # float
message = "Hello"         # str
flag = False              # bool
colors = ["red", "blue"]  # list
person = {"name": "Prab", "age": 25}  # dict

```

### Task

- Create variables of each type with values of your choice.
- Use the `type()` function to print the data type of each variable.

---

**Resource for deeper understanding of data types:**

[Python Official Docs - Built-in Types](https://docs.python.org/3/library/stdtypes.html) — official detailed documentation.

---

## 3. Basic Input and Output (I/O)

### Definition

- **Input** lets your program get data from the user.
- **Output** displays data, usually to the screen.

Python’s `input()` function captures user input as a string. The `print()` function shows output.

### Example

```python
name = input("Enter your name: ")  # takes input as string
print("Hello, " + name + "!")      # outputs greeting

```

### Task

- Write a program asking the user for their age.
- Print a message including the entered age.

---

**Resource for practice:**

[Real Python - Python Input and Output](https://realpython.com/python-input-output/) — easy tutorial with examples.

---

## 4. Functions (Introduction)

### Definition

A **function** is a reusable block of code designed to perform a specific task. Functions help avoid repetition and organise code.

Functions are defined using the `def` keyword and can accept inputs called parameters.

### Example

```python
def greet(name):
    print("Hello, " + name + "!")

greet("Prab")  # calls the function with "Prab"

```

### Task

- Define a function `add_numbers(a, b)` that returns the sum of two numbers.
- Call the function with two numbers and print the result.

---

**Resource to learn more about functions:**

[Python Docs - Defining Functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions) — official tutorial section.

---

# 🧾 Summary of [Day 2: Python Basics](../Section%202%20-%20Python%20for%20AI%20%28Day%202-4%29/Day%202%20-%20Python%20Basics.md)

- Variables hold data and do not require explicit type declarations.
- Python has several key data types including `int`, `float`, `str`, `bool`, `list`, and `dict`.
- Input/output functions allow interaction with the user.
- Functions are reusable code blocks that make programs modular and clean.

---

# 🔭 Preview for [Day 3: Intermediate Python](Day%203%20-%20Intermediate%20Python.md)

Tomorrow, we will explore Python control flow — learning how to make decisions and repeat actions using:

- `if`, `elif`, and `else` statements
- Loops: `for` and `while`

You’ll learn how to control your program’s behaviour dynamically.