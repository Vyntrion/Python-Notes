
# 🐍 Python Full Notes: Basics to Advanced

> **Made with ❤️ by Vyntrion**

---

## 🧠 Introduction to Python

Python is a high-level, interpreted programming language known for its simplicity and readability.  
It was created by **Guido van Rossum** in the late 1980s and released in 1991.

### 💡 Why Learn Python?
- Easy to read and write
- Tons of libraries
- Widely used in web dev, AI, ML, scripting, automation, etc.

---

## 📌 Basics

### ✅ Variables & Data Types
```python
x = 10              # Integer
y = 3.14            # Float
name = "Vanshu"     # String
is_cool = True      # Boolean
```

### ✅ Type Casting
```python
int("5")
str(100)
float("3.14")
bool(0)  # False
```

### ✅ Input & Output
```python
name = input("Enter your name: ")
print("Hello,", name)
```

---

## 🔁 Control Flow

### 🔹 Conditional Statements
```python
if age >= 18:
    print("Adult")
elif age > 13:
    print("Teen")
else:
    print("Child")
```

### 🔹 Loops
```python
# For loop
for i in range(5):
    print(i)

# While loop
count = 0
while count < 5:
    print(count)
    count += 1
```

---

## 📦 Data Structures

### 📋 Lists
```python
fruits = ["apple", "banana"]
fruits.append("orange")
print(fruits[1])  # banana
```

### 📌 Tuples
```python
point = (10, 20)
```

### 🔳 Sets
```python
nums = {1, 2, 2, 3}  # {1, 2, 3}
```

### 🔑 Dictionaries
```python
person = {"name": "Alice", "age": 25}
print(person["name"])
```

---

## 🧩 Functions

### 🔧 Defining & Calling
```python
def greet(name):
    return "Hello " + name

print(greet("Vanshu"))
```

---

## 🧱 Object-Oriented Programming

### 📘 Class & Object
```python
class Car:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    def drive(self):
        print("Vroom!")

my_car = Car("Toyota", "Camry")
my_car.drive()
```

### Core OOP Concepts
- **Encapsulation**
- **Inheritance**
- **Polymorphism**
- **Abstraction**

---

## 🔥 Advanced Python

### ✅ List Comprehension
```python
squares = [x**2 for x in range(5)]
```

### ✅ Lambda Functions
```python
add = lambda x, y: x + y
print(add(3, 4))
```

### ✅ Map, Filter, Reduce
```python
nums = [1, 2, 3, 4]
doubled = list(map(lambda x: x*2, nums))
```

### ✅ Decorators
```python
def decorator(func):
    def wrapper():
        print("Before")
        func()
        print("After")
    return wrapper

@decorator
def say_hi():
    print("Hi")

say_hi()
```

---

## 📂 File Handling

```python
# Write
with open("file.txt", "w") as f:
    f.write("Hello World!")

# Read
with open("file.txt", "r") as f:
    print(f.read())
```

---

## 🧪 Error Handling
```python
try:
    x = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
finally:
    print("Done")
```

---

## 🌐 Modules & Packages

```python
import math
print(math.sqrt(16))
```

### 📦 Installing Packages
```bash
pip install package-name
```

---

## 🧠 Popular Libraries

| Library     | Use                      |
|-------------|---------------------------|
| requests    | HTTP requests             |
| numpy       | Numerical computing       |
| pandas      | Data analysis             |
| matplotlib  | Graph plotting            |
| tkinter     | GUI apps                  |
| pygame      | Game development          |

---

## 💻 Beginner Projects

- Calculator
- To-Do List
- Currency Converter
- Weather App (API)
- Discord Bot
- Chatbot

---

## ✅ Pro Tips

- Comment your code
- Use `try-except` for errors
- Practice daily
- Google is your best friend 😎
- Build projects to learn faster

---

## 🧾 Credits

**Made by Vyntrion**  
Keep learning. Keep coding. 💖
