# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
class Rectangle:

    def __init__(self,length,breadth):

        self.length=length
        
        self.breadth=breadth
    
    def display(self):
    
        print(self.length)
        
        print(self.breadth)

obj=Rectangle(5,3)

obj.display()

## Output
<img width="387" height="265" alt="image" src="https://github.com/user-attachments/assets/e3ba8626-92a6-492a-ac1e-ff837178ef2b" />

## Result
Thus the Python program to implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth` is executed and verified successfully.
