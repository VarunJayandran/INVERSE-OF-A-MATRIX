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
A = np.array([[1, 0, 3],
              [-1, 2, -2],
              [2, 3, -1]])

A_inv = np.linalg.inv(A)

print(A_inv)

```
## Output:

<img width="1026" height="251" alt="image" src="https://github.com/user-attachments/assets/e65b3136-afe1-4b4a-ad02-d523ac3d5250" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

