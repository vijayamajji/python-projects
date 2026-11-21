# python-projects

theme:
dracula
one dark pro
ayu

auto format: Autopep8

notion tracker

Notes:

Python Variables
Variables are used to store data that can be referenced and manipulated during program execution. A variable is essentially a name that is assigned to a value.

Assigning Values to Variables
1. Basic Assignment: Variables are assigned values using the = operator.
x = 5
y = 3.14
z = "Hi"

3. Dynamic Typing: Python is dynamically typed, so the same variable can store different data types during execution.
x = 10
x = "Now a string"

4. Assigning Same Value: Same value can be assigned to multiple variables in a single line.
a = b = c = 100
print(a, b, c)

Output
100 100 100

4. Assigning Different Values: Multiple variables can also be assigned different values in a single line.
x, y, z = 1, 2.5, "Python"
print(x, y, z)

Python variables store references to objects, not the actual values themselves. When a variable is reassigned, it starts referencing a new object while the old unreferenced object becomes eligible for garbage collection.

The scope of the variable determines where it can be accessed in Python program, such as within a function or throughout the program.

--- Deleting a Variable ---
del keyword is used to delete a variable from memory. After deletion, the variable can no longer be accessed.

------Taking multiple inputs from user in Python--------

Python allows users to enter multiple values in a single line or through repeated prompts.

Using input() and split()
One of the simplest ways to take multiple inputs from a user in Python is by using the input() function along with the split() method. The split() method splits a string into a list based on a specified separator (by default, it uses whitespace).

# taking two inputs at a time
x, y, z = input("Values: ").split()
print(x)
print(y)
print(z)

input() takes the full input as a single string.
.split() divides the string into separate components based on whitespace by default.
The values are assigned to individual variables (x, y, z).

---------------------Python Data Types----------------------------------------------------
Data types in Python define the type of value stored in a variable and determine the operations that can be performed on that data. Since Python treats everything as an object, each value is associated with a specific data type.

<img width="800" height="369" alt="image" src="https://github.com/user-attachments/assets/238a1810-c577-4b55-b5f9-0520323c7ab4" />

https://www.datacamp.com/blog/python-data-types

------- string-------------
https://www.geeksforgeeks.org/python/python-string-methods/

https://www.datacamp.com/tutorial/python-string-tutorial

----------

Numpy:

https://www.datacamp.com/cheat-sheet/numpy-cheat-sheet-data-analysis-in-python

https://www.datacamp.com/tutorial/python-numpy-tutorial

https://www.geeksforgeeks.org/python/numpy-tutorial/

----------

Pandas:

https://www.datacamp.com/tutorial/pandas

https://www.datacamp.com/cheat-sheet/pandas-cheat-sheet-for-data-science-in-python

https://www.datacamp.com/tutorial/pandas-tutorial-dataframe-python

https://www.datacamp.com/blog/how-to-learn-pandas

https://www.geeksforgeeks.org/pandas/introduction-to-pandas-in-python/
----


