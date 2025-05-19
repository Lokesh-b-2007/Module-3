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
~~~
def palindrome(a):
    l=[]
    for i in a:
        l.append(i)
    l2=l[::-1]
    if l==l2:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
s=input() 
palindrome(s)
~~~
## Output
![445223458-6d015f49-ab97-4f02-9f8c-e76820135169](https://github.com/user-attachments/assets/f657cc8c-a43d-460d-8171-6653b1a84b23)

## Result
Thus the program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions has been executed successfully.
