# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Input the matrix A 
### Step 2: Perform Gaussian elimination (row reduction) 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Return the count → that’s the rank.
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: VENKATESH.P
#RegisterNumber: 25011427


import numpy as np
A=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
x=np.linalg.matrix_rank(A)
print(x)
```
## Output:
<img width="1920" height="1020" alt="Screenshot 2025-12-14 181615" src="https://github.com/user-attachments/assets/5ff4bf2e-3c87-4b17-b18d-70fe2aff4513" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

