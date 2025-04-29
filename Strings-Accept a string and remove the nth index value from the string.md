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
def remove(s):
   vowels='AEIOUaeiou'
   b=''
   for i in s:
       if i in vowels:
           b+=i
   print(b)


```

## Output
![Screenshot 2025-04-29 180859](https://github.com/user-attachments/assets/3093fabc-f061-47a9-a3f6-50704bb9c868)


## Result
The expected output is achieved
