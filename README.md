# 🐍 Python Basics Before Machine Learning

Welcome to this curated collection of Python fundamentals — the essential building blocks I mastered before diving into machine learning. This folder reflects my journey from syntax to structure, laying the groundwork for scalable, data-driven development.

---

## 📘 Overview

This repository contains beginner-to-intermediate Python scripts and notebooks focused on:

- Writing clean, modular code
- Understanding core programming principles
- Preparing for data workflows and ML pipelines

Whether you're brushing up or just starting out, this folder is designed to help you build confidence and fluency in Python.

---

## 🧠 Topics Covered

| Category               | Concepts Included                                      |
|------------------------|--------------------------------------------------------|
| 🔤 Basics              | Variables, Data Types, Operators                       |
| 🔁 Control Flow        | `if`, `else`, `elif`, `for`, `while` loops             |
| 🧮 Functions           | Defining, calling, lambda expressions                  |
| 📦 Data Structures     | Lists, Tuples, Sets, Dictionaries                      |
| 🧵 Strings             | Manipulation, slicing, formatting                      |
| 📂 File Handling       | Reading, writing, working with files                   |
| 🚨 Error Handling      | `try`, `except`, `finally` blocks                      |
| 🧱 OOP Basics          | Classes, Objects, Inheritance                          |
| 📊 Libraries           | Intro to NumPy and Pandas for ML readiness             |

---

## 🚀 Getting Started


## 📂 Example Scripts

Here are a few sample files included in this folder:

### `01_variables_and_types.py`
```python
name = "Jit"
age = 25
is_developer = True
print(f"{name} is {age} years old and a developer: {is_developer}")
```
### `03_control_flow.py`
```python
score = 85
if score >= 90:
    print("Excellent")
elif score >= 75:
    print("Good")
else:
    print("Keep Improving")
```

### `05_Functions.py`
```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Jit"))
```

### `07_File_handeling.py`
```python
with open("sample.txt", "w") as file:
    file.write("Learning Python is fun!")

with open("sample.txt", "r") as file:
    content = file.read()
    print(content)
```

### `09_OOPs_learn.py`
```python
class Person:
    def __init__(self, name):
        self.name = name

    def greet(self):
        print(f"Hi, I'm {self.name}")

p = Person("Jit")
p.greet()
```



To run any script:

```bash
python filename.py
```
``` Editor
Vs Code
jupyter notebook
```
```Enviroment
python -m venv venv
source venv/bin/activate      # Mac/Linux
venv\Scripts\activate         # Windows
```
