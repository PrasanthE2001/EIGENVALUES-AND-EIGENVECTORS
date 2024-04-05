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
#Program to find the eigen values and eigen vectors.

#Developed by: E Prasanth 

#RegisterNumber: 212221233002

import numpy as np

matrix = np.array([[-2, 2, -3],
                   [2, 1, -6],
                   [-1, -2, 0]])

eigenvalues, eigenvectors = np.linalg.eig(matrix)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
## Output:
![Screenshot (17)](https://github.com/PrasanthE2001/EIGENVALUES-AND-EIGENVECTORS/assets/114572171/c32d4e40-9c93-4835-a503-d3ffb5de4028)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
