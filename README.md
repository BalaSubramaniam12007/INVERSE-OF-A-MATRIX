# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation
### Step 2:
Prepare the lists from each equations and assign in np.aaray() 
### Step 3: 
Using the np.linalg.solve(),we can find the solutions.
### Step 4: 
End the program
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

