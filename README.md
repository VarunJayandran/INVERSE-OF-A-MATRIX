## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(),we can find the inverse of the given marks
### Step 4: End the program.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Varun JC
#RegisterNumber: 212224240179

import numpy as np

matrix = np.array([[2, 1, 1], 
                   [1, 1, 1], 
                   [1, -1, 2]])


inverse_matrix = np.linalg.inv(matrix)
print(inverse_matrix)
```
## Output:

<img width="1407" height="241" alt="478872349-e421c375-c99f-44b4-b5aa-60baa6242352" src="https://github.com/user-attachments/assets/89da3fae-7a2e-44d2-8567-50f47c0fa97c" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

