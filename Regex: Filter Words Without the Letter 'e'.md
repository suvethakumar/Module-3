# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
words = input().split()
result = [word for word in words if not re.search('e', word)]
print("Words without 'e':", result)
```
## Output
<img width="523" height="108" alt="image" src="https://github.com/user-attachments/assets/16eb32d9-84af-4a1f-ad2d-987f2380a0cc" />

## Result
The program has been excecuted successfully
