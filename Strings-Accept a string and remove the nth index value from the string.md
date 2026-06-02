# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
text = input()
index = int(input())
new_text = text[:index] + text[index+1:]
print("String after removing character:", new_text)
```
## Output
<img width="549" height="344" alt="image" src="https://github.com/user-attachments/assets/64e3f067-3c9a-4773-8a62-8853e12a5139" />

## Result
the program has been excecuted successfully
