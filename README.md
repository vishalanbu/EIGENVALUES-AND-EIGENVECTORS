# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
import numpy as np

A=np.array([[4,2],[2,4]])

values,vectors=np.linalg.eig(A)

print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

## Output:
<img width="928" height="419" alt="Screenshot 2026-03-22 114338" src="https://github.com/user-attachments/assets/81eecd52-bd07-4029-aafc-de8fb2539b05" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
