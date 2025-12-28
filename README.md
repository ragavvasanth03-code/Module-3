# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

~~~a
numbers = [14, 16, 18, 22]
total = sum(numbers)
print(total)
~~~

## Output
<img width="876" height="156" alt="Screenshot 2025-10-20 135716" src="https://github.com/user-attachments/assets/3e058f7d-e2c8-4ce5-8e05-9e5e7a8d5cc5" />

## Result
Thus , the program has been executed succesfully.

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
~~~
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print(l1)

~~~
## Output
<img width="824" height="160" alt="Screenshot 2025-10-20 140041" src="https://github.com/user-attachments/assets/8cfe45e7-6bfb-4d25-858a-a311fbff0cdd" />

## Result
Thus , the program has been executed succesfully.

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
~~~
def remove(string):
    n = int(input())
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    print(a)
~~~

## Output
<img width="849" height="199" alt="Screenshot 2025-10-20 141910" src="https://github.com/user-attachments/assets/8e54bb0e-fc22-4695-be4a-81619c2d00f1" />


## Result
Thus , the program has been executed succesfully.

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
string = "google"
reversed_string = string[::-1]
if string == reversed_string:
    print(f"{string} is a palindrome.")
else:
    print(f"{string} is not a palindrome.")

~~~

## Output
<img width="363" height="97" alt="Screenshot 2025-10-20 143217" src="https://github.com/user-attachments/assets/631a12a3-653f-45fc-8ec0-7eb7fb71cebe" />

## Result
Thus , the program has been executed succesfully.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
~~~
x=("s", 8, "a", "v", "n", "g", "u", "r", "c", "e")
print("n" in a)
print(8 in a)
~~~

## Output
<img width="545" height="178" alt="Screenshot 2025-10-20 143939" src="https://github.com/user-attachments/assets/2dfdf654-1590-4a1c-bcd4-574539ff0ac9" />

## Result
Thus , the program has been executed succesfully.
