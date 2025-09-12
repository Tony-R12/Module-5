# Multilevel Inheritance Example in Python

This Python project demonstrates the concept of **Multilevel Inheritance** to collect and display the **name**, **age**, and **location** of a person.

## 🎯 Aim

To write a Python program that uses multilevel inheritance to get and display a person’s name, age, and location.

## 🧠 Algorithm

1. **Parent Class**  
   - `__init__(name)` initializes the `name` attribute.  
   - `getName()` returns the `name`.

2. **Child Class (inherits Parent)**  
   - `__init__(name, age)` initializes `name` using `super()` and adds `age`.  
   - `getAge()` returns the `age`.

3. **Grandchild Class (inherits Child)**  
   - `__init__(name, age, location)` initializes `name` and `age` using `super()` and adds `location`.  
   - `getLocation()` returns the `location`.

4. **Input & Output**  
   - Take user input for name, age, and location.  
   - Create an instance of `Grandchild`.  
   - Print all details using class methods.

## Program
```
class student:
    def __init__(self):
        self.name=name
        self.age=age
        self.id=id
    def fun(self):
        print(self.name)
        print(self.age)
class student2(student):
    def funzz(self):
        print(self.id)
name=input()
age=int(input())
id=int(input())
obj=student2()
obj.fun()
obj.funzz()
```

## Sample Output
<img width="340" height="208" alt="image" src="https://github.com/user-attachments/assets/24a324d4-13d6-417f-8b32-98b1e8f71b78" />

## Results
Thus,the program is successfully created.

