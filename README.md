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
    def mech(self, radius):
        # Calculate the area of the circle
        area = math.pi * radius * radius
        return area
circle = cse()
r = float(input("Enter the radius of the circle: "))
area = circle.mech(r)
print("Area of the circle:", area)

```


## Output
<img width="567" height="75" alt="exp1" src="https://github.com/user-attachments/assets/d69a4de2-6289-481e-9cd7-3b2fb869f56b" />

## Result
The program successfully calculates the area of a circle using classes and objects
## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
# Define two dictionaries
dict1 = {'a': 10, 'b': 20, 'c': 30}
dict2 = {'d': 40, 'b': 50, 'e': 60}

# Function to merge dictionaries
def merge(d1, d2):
    merged_dict = {**d1, **d2}  # Unpacking operator merges dictionaries
    return merged_dict

# Call the function and print the result
merged_result = merge(dict1, dict2)
print("Merged Dictionary:", merged_result)
```
## Output
<img width="998" height="59" alt="exp1" src="https://github.com/user-attachments/assets/d5dd8e3c-0314-4d90-923f-d070ba20f04f" />

## Result
The program successfully merges two dictionaries. All key-value pairs from both dictionaries are combined. If a key exists in both dictionaries (like 'b'), the value from the second dictionary (dict2) overwrites the value from the first dictionary (dict1).
