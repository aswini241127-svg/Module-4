# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
import csv
count = 0
with open('story.txt', 'r') as file:
    for line in file:
        stripped_line = line.lstrip()
        if stripped_line and not stripped_line.startswith('T'):
            count += 1
print("Number of lines not starting with 'T':", count)
```
## Output
<img width="534" height="55" alt="exp1" src="https://github.com/user-attachments/assets/839a2380-28f7-4fb1-aeab-1949ca80289b" />

## Result
The program successfully counts the number of lines in text file
