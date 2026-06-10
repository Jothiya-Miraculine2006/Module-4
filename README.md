# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    def mech(self, r):
        area = math.pi * r * r
        return area
radius = float(input("Enter the radius of the circle: "))
obj = cse()
result = obj.mech(radius)

print("Area of the circle is:", result)
```


## Output
<img width="550" height="260" alt="image" src="https://github.com/user-attachments/assets/7e393f74-7711-42c1-aeec-487e0a0c052e" />



## Result
If the user enters a radius, the program calculates the area using:
# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    def mech(self, r):
        area = math.pi * r * r
        return area
radius = float(input("Enter the radius of the circle: "))
obj = cse()
result = obj.mech(radius)

print("Area of the circle is:", result)
```


## Output
<img width="550" height="260" alt="image" src="https://github.com/user-attachments/assets/7e393f74-7711-42c1-aeec-487e0a0c052e" />



## Result
If the user enters a radius, the program calculates the area using:
# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
my_dict = {
    "banana": "yellow",
    "apple": "red",
    "grape": "purple",
    "orange": "orange"
}


sorted_by_keys = dict(sorted(my_dict.items()))


sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))


print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)
```

## Sample Output
<img width="901" height="416" alt="image" src="https://github.com/user-attachments/assets/dcb07387-0194-46b9-9f18-7f5e0435bc32" />


## Result
The dictionary is successfully sorted by keys and values in alphabetical order.
# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30, 40]

try:
    print(list1[5])  # Invalid index
except IndexError:
    print("You're out of list range")
```

## Output
<img width="575" height="250" alt="image" src="https://github.com/user-attachments/assets/0d8324e8-5ea3-4c95-b809-e1195219db0d" />


## Result
The program handles the IndexError and prints a message when the index is out of range.
# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30, 40]

try:
    print(list1[5])  # Invalid index
except IndexError:
    print("You're out of list range")
```

## Output
<img width="575" height="250" alt="image" src="https://github.com/user-attachments/assets/0d8324e8-5ea3-4c95-b809-e1195219db0d" />


## Result
The program handles the IndexError and prints a message when the index is out of range.
