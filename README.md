# akkkkkk
# Basic arithmetic operations hh
a = 10
b = 5
print("Addition:", a + b)  # Output: 15
print("Subtraction:", a - b)  # Output: 5
print("Multiplication:", a * b)  # Output: 50
print("Division:", a / b)  # Output: 2.0

# If-else statement
age = 20
if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible to vote")

# For loop
for i in range(1, 11):
    print(i)

# While loop
count = 0
while count < 5:
    print(count)
    count += 1

# List operations
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")
fruits.remove("banana")
print(fruits)  # Output: ['apple', 'cherry', 'orange']

# Dictionary
student = {"name": "John", "age": 22, "major": "Physics"}
print(student["name"])  # Output: John
print(student.get("major"))  # Output: Physics

# Function definition
def greet(name):
    return f"Hello, {name}!"
print(greet("Ankit"))  # Output: Hello, Ankit!

# Lambda function
square = lambda x: x**2
print(square(5)) # Output: 25

# List comprehension
numbers = [1, 2, 3, 4, 5]
squares = [x**2 for x in numbers]
print(squares) # Output: [1, 4, 9, 16, 25]
