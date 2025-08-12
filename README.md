# my-painting
my painting this favorite
# ==========================
# 1. Hello World with a twist
# ==========================
from datetime import datetime

name = input("What's your name? ")
time_now = datetime.now().strftime("%H:%M:%S")
print(f"Hello, {name}! The current time is {time_now}. Have a great day!")

# ==========================
# 2. Simple Calculator
# ==========================
def add(a, b): return a + b
def subtract(a, b): return a - 
def multiply(a, b): return a * b
def divide(a, b): return a / b if b != 0 else "Error: Division by zero!"

print("\nSimple Calculator")
x = float(input("Enter first number: "))
y = float(input("Enter second number: "))

print(f"Add: {add(x, y)}")
print(f"Subtract: {subtract(x, y)}")
print(f"Multiply: {multiply(x, y)}")
print(f"Divide: {divide(x, y)}")

# ==========================
# 3. Random Password Generator
# ==========================
import random
import string

def generate_password(length=12):
    characters = string.ascii_letters + string.digits + string.punctuation
    return ''.join(random.choice(characters) for _ in range(length))

print("\nGenerated Password:", generate_password(16))
