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
def palindrome(a):
    x1=a[::-1]
    if a==x1:
       print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
    
    
        
        
string =input()
palindrome(string)
```
Add code here

## Output
<img width="948" height="157" alt="image" src="https://github.com/user-attachments/assets/d58d5b71-59e2-4b70-b01f-7f83c297f7a1" />

## Result
