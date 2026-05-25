## Loops in Python: Palindrome Number Checker

**NAME : OMKAR VARMA S**
**REG NO : 212224240108**

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num = 1221
original = num
reverse = 0
while num > 0:
    digit = num % 10
    reverse = reverse * 10 + digit
    num = num // 10
if original == reverse:
    print(original, "is a Palindrome")
else:
    print(original, "is not a Palindrome")
```
## Output

<img width="314" height="118" alt="image" src="https://github.com/user-attachments/assets/040b596c-f4f6-48de-a319-f8bfdbf95696" />


## Result
program has been excecuted successfully and the result was obtained
