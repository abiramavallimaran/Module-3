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
    # Step 2: Read the index from user
    n = int(input("Enter the index to remove: "))
    a = ""
    for i in range(len(s)):
        if i != n:  # Step 5: Skip the character at index n
            a += s[i]
    return a
string_input = input("Enter a string: ")
result = remove(string_input)
print("String after removing character:", result)

## Output
Enter a string: hello
Enter the index to remove: 1
String after removing character: hllo
```
## Result
Thus Removed a character at a specified index from a given string.
