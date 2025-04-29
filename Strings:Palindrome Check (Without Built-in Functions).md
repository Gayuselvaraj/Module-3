# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```
user_input = input()


left = 0
right = len(user_input) - 1

is_palindrome = True
while left < right:
    if user_input[left] != user_input[right]:
        is_palindrome = False
        break
    left += 1
    right -= 1


if is_palindrome:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")


```

## Output

![Screenshot 2025-04-29 181433](https://github.com/user-attachments/assets/a0e97791-f4fb-4781-8330-a887b3eb3f9c)

## Result
The expected output is acheived
