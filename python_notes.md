# Python Notes

This file contains notes on Python programming.

## Variables

Variables are containers for storing data values.

### Variable Types
- **int**: Integer numbers (e.g., `age = 25`)
- **float**: Decimal numbers (e.g., `price = 19.99`)
- **str**: Text strings (e.g., `name = "John"`)
- **bool**: True/False values (e.g., `is_student = True`)

### Variable Assignment
```python
# Creating variables
name = "Alice"
age = 20
gpa = 3.8
is_enrolled = True


## Loops

Loops allow you to repeat code multiple times.

### For Loop
```python
# Loop through a range
for i in range(5):
    print(i)

# Loop through a list
fruits = ["apple", "banana", "orange"]
for fruit in fruits:
    print(fruit)

# While Loop

count = 0
while count < 5:
    print(count)
    count += 1

# Functions
Functions are reusable blocks of code.

Defining Functions
def greet(name):
    return f"Hello, {name}!"

# Calling the function
message = greet("Alice")
print(message)
Function with Multiple Parameters
def add_numbers(a, b):
    return a + b

result = add_numbers(5, 3)
print(result)  # Output: 8
Function with Default Parameters

def introduce(name, age=18):
    print(f"My name is {name} and I am {age} years old")

introduce("Bob")  # Uses default age
introduce("Alice", 25)  # Uses provided age