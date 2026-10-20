### Object Oriented Programming using Python


| Name     | Aditya Sharma 
| -------- | :------: 
| RollNo.  | 26570005   
| Dept.    | BSC (H) Computer Science
| Semester | 1  
|Tool      | Python 3


## Practical 1: Roots of a Quadratic Equation

Question: Write a program to find the roots of a quadratic equation.

Concepts used: cmath, discriminant, if / elif / else, complex roots

Program 

# Practical 1: WAP to find the roots of a quadratic equation  (ax^2 + bx + c = 0)
import cmath


def quadratic_roots(a, b, c):
    """Return the two roots of ax^2 + bx + c = 0 (real or complex)."""
    d = b ** 2 - 4 * a * c            # discriminant
    root1 = (-b + cmath.sqrt(d)) / (2 * a)
    root2 = (-b - cmath.sqrt(d)) / (2 * a)
    return d, root1, root2


print("Quadratic equation: ax^2 + bx + c = 0")
a = float(input("Enter a: "))
b = float(input("Enter b: "))
c = float(input("Enter c: "))

if a == 0:
    print("'a' cannot be 0 - this is not a quadratic equation.")
    if b != 0:
        print("It is linear, with root x =", -c / b)
else:
    d, r1, r2 = quadratic_roots(a, b, c)
    print("Discriminant =", d)
    if d > 0:
        print("Roots are real and distinct.")
        print("x1 =", r1.real, "\nx2 =", r2.real)
    elif d == 0:
        print("Roots are real and equal.")
        print("x1 = x2 =", r1.real)
    else:
        print("Roots are complex conjugates.")
        print("x1 =", r1, "\nx2 =", r2)


## Output

<img width="347" height="128" alt="image" src="https://github.com/user-attachments/assets/2bc2f0c2-4cb5-436a-9153-2caeaed2c68c" />
