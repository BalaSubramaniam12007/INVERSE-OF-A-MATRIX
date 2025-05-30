# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

## Step 1:
Import the `numpy` module to use built-in functions for matrix operations.

## Step 2:
Represent the system of equations in matrix form:
- Define the **coefficient matrix** `A` using `np.array()`.
- Define the **constant matrix** `B` using `np.array()`.

## Step 3:
Use the NumPy function `np.linalg.solve(A, B)` to solve for the unknown variables.

## Step 4:
Print the solution to display the values of the variables.

## Step 5:
End the program.

## Program:
```python
#Program to find the inverse of a matrix.
#Developed by: BALASUBRAMAINAM 
#RegisterNumber:24901213

import numpy as np

A = np.array([[6, 2, 3],
              [3, 1, 1],
              [10, 3, 4]])

inverse = np.linalg.inv(A)
print(inverse)

```
## Output:
![image](https://github.com/user-attachments/assets/a181e58a-fa8e-4185-aef0-69106cfad337)

## Result:
Thus the inverse of given matrix is successfully solved using python program

