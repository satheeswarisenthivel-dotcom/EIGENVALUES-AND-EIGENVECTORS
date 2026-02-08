# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: Form the characteristic equation using the given matrix
## Step 2: Solve the equation to obtain eigenvalues
## Step 3: Substitute each eigenvalue in the matrix equation
## Step 4: Solve the equations to obtain the corresponding eigenvectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: s.satheeswari 
#RegisterNumber: 25017493
import numpy as np
a=([-2,2,-3],[2,1,-6],[-1,-2,0])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1238" height="405" alt="Screenshot 2026-02-08 205800" src="https://github.com/user-attachments/assets/75974f4a-3fc3-4ecf-b5b4-ff90eade029e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
