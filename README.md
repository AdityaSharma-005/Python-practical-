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

<img width="1490" height="552" alt="image" src="https://github.com/user-attachments/assets/235b52b3-bf17-4d3d-8b67-892d4fda3e95" />

## Output

<img width="347" height="128" alt="image" src="https://github.com/user-attachments/assets/2bc2f0c2-4cb5-436a-9153-2caeaed2c68c" />

## Practical 2: Prime Numbers
Question: Write a program to accept a number 'n' and

a. Check if 'n' is prime
b. Generate all prime numbers till 'n'
c. Generate first 'n' prime numbers
This program may be done using functions.

Concepts used: functions, while loop, list comprehension

Program

<img width="1522" height="755" alt="image" src="https://github.com/user-attachments/assets/52a7fd0e-0713-40cf-a5b0-6610c1f5d141" />

Output

<img width="751" height="161" alt="image" src="https://github.com/user-attachments/assets/3d71e108-47bc-48a4-baf6-d5670ce626c2" />

##  Practical 3: Pyramid and Reverse Pyramid

Question: Write a program to create a pyramid of the character '*' and a reverse pyramid.

Concepts used: nested logic with string repetition (" " * k + "*" * m)

Program

<img width="1430" height="376" alt="image" src="https://github.com/user-attachments/assets/e54b9a14-fffa-44a1-a067-385a0c705136" />

Output

<img width="642" height="342" alt="image" src="https://github.com/user-attachments/assets/4907576a-7ae4-4dab-bb11-af2c4960b95a" />

## Practical 4: Character Check

Question: Write a program that accepts a character and performs the following:

a. print whether the character is a letter or numeric digit or a special character.
b. if the character is a letter, print whether the letter is uppercase or lowercase
c. if the character is a numeric digit, prints its name in text (e.g., if input is 9, output is NINE)
Concepts used: isalpha(), isupper(), isdigit(), dictionary lookup

Program

<img width="1363" height="410" alt="image" src="https://github.com/user-attachments/assets/f2260cd3-6330-4256-8511-bc1529578d88" />

Output

<img width="782" height="233" alt="image" src="https://github.com/user-attachments/assets/342d9944-8e0b-42ca-ae97-3bd737d355e6" />

## Practical 5: Operations on a String

Question: Write a program to perform the following operations on a string

a. Find the frequency of a character in a string.
b. Replace a character by another character in a string.
c. Remove the first occurrence of a character from a string.
d. Remove all occurrences of a character from a string.
Concepts used: string traversal, find(), slicing, functions

Program

<img width="1491" height="711" alt="image" src="https://github.com/user-attachments/assets/96cb8647-6ee0-41f6-a753-47574f658815" />

Output

<img width="767" height="232" alt="image" src="https://github.com/user-attachments/assets/b91383d2-1f7e-475b-8522-0e25a0151616" />

## Practical 6: Swap the First n Characters of Two Strings
Question: Write a program to swap the first n characters of two strings.

Concepts used: string slicing and concatenation

Program

<img width="835" height="307" alt="image" src="https://github.com/user-attachments/assets/02e843de-e56a-405d-b24e-3f0825f2f065" />

Output

<img width="771" height="147" alt="image" src="https://github.com/user-attachments/assets/3b8314a2-0e82-408d-8b46-414a5ea29065" />

## Practical 7: Indices of a Substring

Question: Write a function that accepts two strings and returns the indices of all the occurrences of the second string in the first string as a list. If the second string is not present in the first string then it should return -1.

Concepts used: str.find(sub, start), lists, return values

Program 


Output


## Practical 8: Cubes of Even Integers
Question: Write a program to create a list of the cubes of only the even integers appearing in the input list (may have elements of other types also) using the following:

a. 'for' loop
b. list comprehension
Concepts used: isinstance(), for loop, list comprehension (bool is excluded on purpose, because True is an int in Python)

Program

<img width="1012" height="417" alt="image" src="https://github.com/user-attachments/assets/ef1d9571-ba71-41f6-bd97-0a85564536ec" />

Output

<img width="657" height="177" alt="image" src="https://github.com/user-attachments/assets/94e7842f-2889-490f-bc05-5e776554b20a" />

## Practical 9: File Handling

Question: Write a program to read a file and

a. Print the total number of characters, words and lines in the file.
b. Calculate the frequency of each character in the file. Use a variable of dictionary type to maintain the count.
c. Print the words in reverse order.
d. Copy even lines of the file to a file named 'File1' and odd lines to another file named 'File2'.
Concepts used: open() with with, readlines(), dictionary counting, split(), enumerate()

Program

<img width="1497" height="757" alt="image" src="https://github.com/user-attachments/assets/73fa2848-c06d-445e-b977-386077f63ea8" />
<img width="682" height="165" alt="image" src="https://github.com/user-attachments/assets/fe1d102d-fe04-4a99-a53b-1f8bccaaed8b" />

Output

<img width="842" height="440" alt="image" src="https://github.com/user-attachments/assets/a0ef5025-4f66-483d-837e-05e0e3d18576" />

## Practical 10: Dictionary of Cubes

Question: Write a function that prints a dictionary where the keys are numbers between 1 and 5 and the values are cubes of the keys.

Concepts used: functions, dictionaries, range()

Program

<img width="972" height="255" alt="image" src="https://github.com/user-attachments/assets/b3f345c3-6538-4fc5-a151-78bd4b811082" />

Output

<img width="637" height="162" alt="image" src="https://github.com/user-attachments/assets/a9399610-33f9-45f4-8b55-1a8585d9e556" />

## Practical 11: Tuple Operations

Question: Consider a tuple t1=(1, 2, 5, 7, 9, 2, 4, 6, 8, 10). Write a program to perform following operations:

a. Print half the values of the tuple in one line and the other half in the next line.
b. Print another tuple whose values are even numbers in the given tuple.
c. Concatenate a tuple t2=(11,13,15) with t1.
d. Return maximum and minimum value from this tuple

Concepts used: tuple slicing, tuple() with a generator, concatenation (+), max() / min()

Program

<img width="1053" height="567" alt="image" src="https://github.com/user-attachments/assets/6c2cd8e1-48b1-4b89-81f6-22ad313a212d" />

Output

<img width="657" height="257" alt="image" src="https://github.com/user-attachments/assets/c46f5253-4692-47bd-8943-c52f745bc531" />

## Practical 12: Employee Class

Question: Define a class Employee that stores information about employees in the company. The class should contain the following:

(i) data members: count (to keep a record of all the objects being created for this class) and for every employee: an employee number, Name, Dept, Basic, DA and HRA.
(ii) function members:
a. __init__ method to initialize and/or update the members. Add statements to ensure that the program is terminated if any of Basic, DA and HRA is set to a negative value.
b. function salary, that returns salary as the sum of Basic, DA and HRA.
c. __del__ function to decrease the number of objects created for the class.
d. __str__ function to display the details of an employee along with the salary of an employee in a proper format.
Concepts used: class attribute (count), __init__, __del__, __str__, sys.exit()

Program
```python
# Practical 12: Define a class Employee that stores information about employees in the company.
# Data members : count (number of objects created) and, for every employee, an employee number,
#                Name, Dept, Basic, DA and HRA.
# Function members:
#   a. __init__ to initialize and/or update the members; the program is terminated if any of
#      Basic, DA and HRA is set to a negative value
#   b. salary, which returns Basic + DA + HRA
#   c. __del__ to decrease the number of objects created for the class
#   d. __str__ to display the details of an employee along with the salary in a proper format
import sys


class Employee:
    count = 0                                   # class attribute: number of live Employee objects

    def __init__(self, emp_no, name, dept, basic, da, hra):
        self._counted = False
        self.emp_no = emp_no
        self.name = name
        self.dept = dept
        self.update(basic, da, hra)             # validates Basic, DA and HRA
        Employee.count += 1                     # reached only if the values were valid
        self._counted = True

    def update(self, basic, da, hra):
        """Set (or change) Basic, DA and HRA. A negative value terminates the program."""
        if basic < 0 or da < 0 or hra < 0:
            print("Error: Basic, DA and HRA cannot be negative. Terminating the program.")
            sys.exit(1)
        self.basic = basic
        self.da = da
        self.hra = hra

    def salary(self):
        return self.basic + self.da + self.hra

    def __del__(self):
        if getattr(self, "_counted", False):    # an object that failed validation was never counted
            Employee.count -= 1

    def __str__(self):
        return (f"Employee No : {self.emp_no}\n"
                f"Name        : {self.name}\n"
                f"Department  : {self.dept}\n"
                f"Basic       : Rs. {self.basic:,.2f}\n"
                f"DA          : Rs. {self.da:,.2f}\n"
                f"HRA         : Rs. {self.hra:,.2f}\n"
                f"Salary      : Rs. {self.salary():,.2f}")


e1 = Employee(101, "Shivam Pal", "Computer Science", 30000, 12000, 8000)
e2 = Employee(102, "Aman Verma", "Mathematics", 28000, 11000, 7500)
e3 = Employee(103, "Neha Singh", "Physics", 32000, 12500, 8500)

print(e1)
print("-" * 40)
print(e2)
print("-" * 40)
print(e3)
print("-" * 40)
print("Employees created:", Employee.count)

del e3                                          # object destroyed -> __del__ runs
print("After deleting one employee:", Employee.count)

e1.update(35000, 14000, 9000)                   # update the pay components of e1
print("\nAfter updating e1:")
print(e1)

print("\nTrying to create an employee with a negative DA ...")
e4 = Employee(104, "Test User", "Chemistry", 25000, -500, 7000)
print("This line is never reached.")
```

Output

<img width="838" height="435" alt="image" src="https://github.com/user-attachments/assets/bfdbdf30-65f5-42e8-9ed0-96210b0d814a" />

## Practical 13: Class 2DPoint

Question: Write a program to define a class "2DPoint" with coordinates x and y as attributes. Create relevant methods and print the objects. Also define a method distance to calculate the distance between any two point objects.

A Python class name cannot begin with a digit, so the class is named Point2D.

Concepts used: classes, objects, __str__, math.sqrt()

Program 

