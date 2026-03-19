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
  class R:
    def __init__(self, l, w):
        self.__l = l
        self.__w = w
    def display(self):
        print(self.__l)
        print(self.__w)
rect = R(5,3)
rect.display()
```
## Output
<img width="242" height="114" alt="image" src="https://github.com/user-attachments/assets/2e928566-0362-4f88-b303-d9e54e5dba56" />

## Result
Thus, the program to implement Encapsulation in Python has been executed successfully.
