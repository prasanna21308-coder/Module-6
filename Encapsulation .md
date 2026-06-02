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
```
class Rectangle:
    def __init__(self, length, breadth): 
        self.__length = length 
        self.__breadth = breadth 
        self.display_values()

    def display_values(self):
        print(f"Length: {self.__length}")
        print(f"Breadth: {self.__breadth}")
rect = Rectangle(10, 5)
```
## Output
<img width="1573" height="501" alt="image" src="https://github.com/user-attachments/assets/747f1c0a-7fdf-4afa-b1bf-bf94aa10dc80" />

## Result
Thus To implement Encapsulation in Python by defining a class Rectangle with private member variables __length and __breadth. Hence the code has been executed successfully.
