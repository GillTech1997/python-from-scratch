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
