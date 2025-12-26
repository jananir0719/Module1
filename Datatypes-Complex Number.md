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
<img width="373" height="162" alt="image" src="https://github.com/user-attachments/assets/ec84a794-e1fc-4653-83d2-958913136c69" />


## Result
Thus, the Python program to create a complex number from two integers and display its real and imaginary parts was executed successfully.
