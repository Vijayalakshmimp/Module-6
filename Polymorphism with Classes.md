# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
class Beans: 

     def type(self): 

       print("Vegetable") 
     
     def color(self):
     
       print("Green")
       
class Mango:

     def type(self): 

       print("Fruit") 
     
     def color(self): 
     
       print("Yellow")      

obj_beans = Beans() 

obj_mango = Mango() 

obj_beans.type()

obj_beans.color()

obj_mango.type()

obj_mango.color()

## Output
![IMG-20250902-WA0004 1](https://github.com/user-attachments/assets/85280556-8425-40c4-8c56-e6983a186755)

## Result
Thus the Python program to create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism is executed and verified successfully.
