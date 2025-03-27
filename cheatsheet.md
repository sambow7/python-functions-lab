# 🧪 Functions Lab Cheatsheet

## ✅ Exercise 1: Calculate Area of a Triangle
**Goal:** Calculate the area using (base * height) / 2  
**Code:**
```python
def calculate_area_triangle(base, height):
    return (base * height) / 2
```

## ✅ Exercise 2: Calculate Simple Interest
**Goal:** Use (principal * rate * time) / 100  
**Code:**
```python
def simple_interest(principal, rate, time):
    return (principal * rate * time) / 100
```

## ✅ Exercise 3: Apply a Discount
**Goal:** Apply a percentage discount  
**Code:**
```python
def apply_discount(price, discount_percent):
    return price * (1 - discount_percent / 100)
```

## ✅ Exercise 4: Convert Temperature
**Goal:** Convert 'C' to 'F' and vice versa  
**Code:**
```python
def convert_temperature(temp, unit):
    if unit == 'C':
        return (temp * 9/5) + 32
    elif unit == 'F':
        return (temp - 32) * 5/9
```

## ✅ Exercise 5: Sum to N
**Goal:** Return sum from 1 to n  
**Code:**
```python
def sum_to(n):
    return sum(range(1, n + 1))
```

## ✅ Exercise 6: Find the Largest Number
**Goal:** Return largest of 3 numbers  
**Code:**
```python
def largest(a, b, c):
    return max(a, b, c)
```

## ✅ Exercise 7: Calculate a Tip
**Goal:** Return bill * tip_percent / 100  
**Code:**
```python
def calculate_tip(bill, percent):
    return bill * (percent / 100)
```

## ✅ Exercise 8: Calculate Product of Numbers
**Goal:** Multiply arbitrary number of arguments  
**Code:**
```python
def product(*args):
    result = 1
    for num in args:
        result *= num
    return result
```

## ✅ Exercise 9: Basic Calculator
**Goal:** Use op string to determine math action  
**Code:**
```python
def basic_calculator(a, b, op):
    if op == "add":
        return a + b
    elif op == "subtract":
        return a - b
    elif op == "multiply":
        return a * b
    elif op == "divide":
        return a / b
    else:
        return "Invalid operation"
```
