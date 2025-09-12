# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```
class Person:
    def __init__(self,name,age):
        print("Person Created")
        self.name = name
        self.age = age
    def printInfo(self):
        print(self.name,self.age)
   #add destructor
        print(self.name,"Object Destroyed")

name=input()
age=int(input())
P1=Person(name,age)
#P2=Person("Joe",34)
P1.printInfo()
#P2.printInfo()
del P1
```

## 🧪 Output
<img width="650" height="295" alt="image" src="https://github.com/user-attachments/assets/408d427a-b37b-4ad7-96f8-4723e7276cd9" />


## Result
Thus, the program is successfully created.

