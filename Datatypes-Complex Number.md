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
```
# Create and display a complex number

real = int(input("Enter the real part: "))
imag = int(input("Enter the imaginary part: "))

c = complex(real, imag)

print("Complex number:", c)
print("Real part:", c.real)
print("Imaginary part:", c.imag)
```

## Output
<img width="1031" height="707" alt="image" src="https://github.com/user-attachments/assets/4b52db11-568a-41f9-b6b2-d5d70bda3993" />



## Result
Thus, the Python program to create a complex number from two integers and display its real and imaginary parts was executed successfully.
