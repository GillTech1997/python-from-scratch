# My Python Basics Learning 🐍

Welcome to my Python learning repository! Here, I'm documenting my journey through the fundamentals of Python programming. I'm just getting started, but I’m excited to keep learning and sharing my progress!

## What I Learned So Far:

1. **Variables:**
   - Variables are used to store data and can change types after assignment. No need to declare the type!
   - Example:
     ```python
     x = 5   # integer
     x = "Hello"   # now a string!
     ```

2. **Casting Variables:**
   - You can specify the type using casting functions like `str()`, `int()`, and `float()`.
     ```python
     x = str(5)   # now '5' as a string
     y = float(5) # now 5.0 as a float
     ```

3. **Global and Local Variables:**
   - Variables created inside functions are local, but we can make them global using the `global` keyword.
     ```python
     global x
     x = "awesome"
     ```

4. **Variable Naming:**
   - Variables can be named using letters, numbers, and underscores, but they must start with a letter or underscore.
   - They are case-sensitive: `myVar`, `MyVar`, and `myvar` are different!

5. **Unpacking Collections:**
   - Python allows us to assign values from lists to multiple variables at once.
     ```python
     fruits = ["apple", "banana", "cherry"]
     x, y, z = fruits
     ```

## Why I Created This Repo:
This repository is a place for me to practice and reflect on what I’ve learned. It’s an ongoing project, and I plan to expand it as I learn more advanced topics.

## How to Explore:
Feel free to browse through my code and follow along with my journey into Python. You can clone the repo if you’d like to try out the examples:
```bash
git clone https://github.com/yourusername/python-basics


# Python Data Types

This repository covers Python's built-in data types, which are crucial for understanding how variables store and manipulate data in Python.

## Built-in Data Types

Python provides several built-in data types, categorized as follows:
- **Text Type**: `str`
- **Numeric Types**: `int`, `float`, `complex`
- **Sequence Types**: `list`, `tuple`, `range`
- **Mapping Type**: `dict`
- **Set Types**: `set`, `frozenset`
- **Boolean Type**: `bool`
- **Binary Types**: `bytes`, `bytearray`, `memoryview`
- **None Type**: `NoneType`

## Examples

### Checking Data Types
```python
x = 6
print(type(x))  # Output: <class 'int'>
```

### Assigning Specific Data Types
```python
x = "Hello World"         # str
x = 20                    # int
x = 20.5                  # float
x = ["apple", "banana"]    # list
```

## Setting Specific Data Types with Constructor Functions
```python
x = str("Hello World")      # str
x = int(20)                 # int
x = list(("apple", "banana"))  # list
```

---

This repository also includes detailed information on Python's numeric types, string methods, and other core operations.

