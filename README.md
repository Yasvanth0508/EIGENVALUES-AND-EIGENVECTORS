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
```
#Program to find the eigen values and eigen vectors.
#Developed by: RAKESH RATHNA M 
#RegisterNumber:212224040265
import numpy as np

A = np.array([[4, 2],
              [2, 4]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:
![450571995-727f487f-e0e7-42b6-aab8-a59865b5e6f8](https://github.com/user-attachments/assets/699f9220-5950-45e5-a122-cc71994729a1)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
