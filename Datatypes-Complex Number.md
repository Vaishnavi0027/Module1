# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
~~~
# Read integer inputs from the user
a = int(input("Enter the real part: "))
b = int(input("Enter the imaginary part: "))

# Create a complex number
x = complex(a, b)

# Print the complex number and its parts
print("The complex number is:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)
~~~

## Output
<img width="1124" height="680" alt="439077667-5e90e422-3b75-474f-bbb2-6b3ed329e0b7" src="https://github.com/user-attachments/assets/e9ecde7b-05a6-4211-a5d6-c239fd302684" />

## Result
Program executed successfully
