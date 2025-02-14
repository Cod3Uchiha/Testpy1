## Calculator

### Overview
This is a simple calculator that can perform basic arithmetic operations (addition, subtraction, multiplication, and division).


### Installation
```
pip install calculator
```

### Usage
```
from calculator import Calculator

calculator = Calculator()

# Perform addition
result = calculator.add(1, 2)
print(result)  # Output: 3

# Perform subtraction
result = calculator.subtract(5, 3)
print(result)  # Output: 2

# Perform multiplication
result = calculator.multiply(3, 4)
print(result)  # Output: 12

# Perform division
result = calculator.divide(10, 2)
print(result)  # Output: 5.0
```

### Files and their content

#### calculator.py
```
class Calculator:
    def __init__(self):
        pass
    
    def add(self, a, b):
        return a + b

    def subtract(self, a, b):
        return a - b

    def multiply(self, a, b):
        return a * b

    def divide(self, a, b):
        return a / b
```

### Documentation
#### Class
##### `Calculator`
The `Calculator` class provides methods for performing basic arithmetic operations.

##### Methods
* `add(self, a, b)`: Adds two numbers and returns the result.
* `subtract(self, a, b)`: Subtracts one number from another and returns the result.
* `multiply(self, a, b)`: Multiplies two numbers and returns the result.
* `divide(self, a, b)`: Divides one number by another and returns the result.