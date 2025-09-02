# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
from abc import ABC, abstractmethod

class Shape(ABC):

    @abstractmethod
    
    def calculate_area(self):
    
        pass
        
class Rectangle(Shape):


    length = 5
    
    breadth =3 
    
    def calculate_area(self):
    
        return self.length * self.breadth

class Circle(Shape):
    
    radius = 4
    
    def calculate_area(self):
    
        return 3.14*4*4
        
r=Rectangle()

r.calculate_area()

c=Circle()

c.calculate_area()

print("Area of a rectangle:", r.calculate_area())

print("Area of a circle:", c.calculate_area())

## Output
<img width="755" height="266" alt="image" src="https://github.com/user-attachments/assets/38a35402-e571-4f9e-9b8d-ebac784a173d" />

## Result
Thus the Python program to create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle` is executed and verified successfully.
