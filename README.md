## Ex1 : Built-in Functions -Binary Conversion Using Built-in Functions in Python

## Aim

To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

## Algorithm

1. Assign the value 16 to a variable a.
2. Use the built-in bin() function to convert the number to binary.
3. Print the result.

## Program
```
a = 16 print(bin(a))
```
## Output

<img width="575" height="46" alt="Screenshot 2026-03-29 174624" src="https://github.com/user-attachments/assets/7cd61b15-2166-48bd-a5ec-a3a4e8e0bd9f" />

## Result

The program successfully converts the number 16 into its binary representation and displays the result as 0b10000 on the screen.


## Ex2 : Functions in Python: Modulo Calculator

## Aim

To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

## Algorithm

1. Define a function called result that takes two arguments a and b.
2. Inside the function, compute the modulo using a % b.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the result function with the user-provided values.
   
## Program
```
add = lambda a, b: a + b
result = add(4, 5)
print("Sum is:", result)
```
## Output

<img width="332" height="70" alt="Screenshot 2026-03-29 175012" src="https://github.com/user-attachments/assets/e0aa5b63-2784-4c97-ad0b-4478292dd9ef" />

## Result

The program successfully created lambda function to find the sum.


## Ex3 : Lambda Function in Python: Addition of Two Numbers

## Aim

To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

## Algorithm

1. Get two integer inputs from the user.
2. Use a lambda function to define a function f that returns a + b.
3. Call the function with the user inputs and print the result.

## Program
```
from math import factorial
rows = int(input("Enter the number of rows: "))
for i in range(rows):
    print(" " * (rows - i), end="")
    for j in range(i + 1):
        print(factorial(i) // (factorial(j) * factorial(i - j)), end=" ")
    print()
```
## Output

<img width="340" height="120" alt="Screenshot 2026-03-29 175312" src="https://github.com/user-attachments/assets/74112290-7a87-4132-b047-8c690c0695ed" />

## Result

The Python program successfully takes the number of rows as input from the user and generates Pascal’s Triangle.


## Ex4 : Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

## Aim

To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

## Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
     Print appropriate spaces to shape the triangle.
     Compute values using the formula:
     [ C(n, k) = \frac{n!}{k!(n-k)!} ]
5. Print all rows of Pascal’s Triangle.
6. End the program.
   
## Program
```
from math import factorial
rows = int(input("Enter the number of rows: "))
for i in range(rows):
    print(" " * (rows - i), end="")
    for j in range(i + 1):
        print(factorial(i) // (factorial(j) * factorial(i - j)), end=" ")
    print()
```
## Output

<img width="328" height="118" alt="Screenshot 2026-03-29 175844" src="https://github.com/user-attachments/assets/81d05e9a-2d93-46b3-8a8e-793941e3b42d" />

## Result

The Python program successfully takes the number of rows as input from the user and generates Pascal’s Triangle.


## Ex5 : Loops in Python: Palindrome Number Checker

## Aim

To write a Python program that checks whether a given number is a palindrome using loops.

## Algorithm

1. Get input from the user and assign it to a variable num.
2. Assign the value of num to a temporary variable temp.
3. Initialize a variable rev to 0 (used to store the reversed number).
4.  Use a while loop to reverse the digits:
      While temp > 0:
          rev = (10 * rev) + temp % 10
          temp = temp // 10
5. After the loop, compare rev with num:
     If equal, print that the number is a palindrome.
     Else, print that it is not a palindrome.
   
## Program
```
def find_modulo(a, b):
    return a % b
result = find_modulo(17, 5)
print("17 % 5 =", result)
```

## Output

<img width="185" height="53" alt="Screenshot 2026-03-29 180150" src="https://github.com/user-attachments/assets/dd4ee8fc-8fa0-401e-81b3-f599162e5a63" />

## Result

The program successfully defines a function and returns the modulo of the two inputs.
