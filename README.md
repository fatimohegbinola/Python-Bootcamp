
# Python Bootcamp Project

Welcome to my Python Bootcamp repository! This contains my work and exercises completed during the bootcamp, focusing on Python programming fundamentals.

## Project Overview

The following topics were covered:
- **Basic Python Syntax**: Variables, loops, conditionals, etc.
- **String Operations**: Concatenation, string methods like `.title()` and `.upper()`.
- **Comparative Operators**: Understanding `==`, `!=`, `>`, and their usage in conditional statements.
- **If Statements**: Writing basic conditional logic.
- **Data Types**:
  - **Integers**: Working with numeric data types.
  - **Strings**: Manipulating text data.
  - **Lists**: Creating and modifying lists.
  - **Tuples**: Using immutable sequences.

## Code Examples

### 1. Working with Integer Data Type
```python
x = 10  # Assigning 10 to x
print(x)  # Outputs 10

# Simple operations
print(2 + 2)  # Outputs 4

# Data type check
print(type(88))  # Outputs <class 'int'>
```

### 2. String Data Type Operations
```python
firstname = 'fatimoh'
lastname = 'egbinola'
my_name = firstname + ' ' + lastname

print(my_name)  # Outputs 'fatimoh egbinola'
print(my_name.title())  # Outputs 'Fatimoh Egbinola'
print(my_name.upper())  # Outputs 'FATIMOH EGBINOLA'
```

### 3. Comparative Operators and If Statements
```python
# Comparative operations
print(1 != 2)  # Outputs True
print(1 == 2)  # Outputs False
print(1 > 2)   # Outputs False

# If statement
x = 10
if x == 10:
    print('Yes')  # Outputs 'Yes'

# Checking a string with if statement
name = 'James'
if name == 'James':
    print('Correct')  # Outputs 'Correct'
```

### 4. Lists and Tuples
```python
# List: Mutable sequence of items
fruits = ['apple', 'banana', 'cherry']
print(fruits[0])  # Outputs 'apple'
print(fruits[2])  # Outputs 'cherry'

# Tuple: Immutable sequence of items
dimensions = (1920, 1080)
print(dimensions[0])  # Outputs 1920
```


## Prerequisites

- Python 3.x
- Jupyter Notebook installed
- Basic understanding of Python programming

