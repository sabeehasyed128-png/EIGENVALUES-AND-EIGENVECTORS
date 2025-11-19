# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SABEEHA PARVEEN.K
#RegisterNumber:25016301
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
Values,Vectors = np.linalg.eig(A)
print(f"Eigen values are {Values} and Eigen Vectors are {Vectors}")
```
## Output:
<img width="1497" height="901" alt="EXP4" src="https://github.com/user-attachments/assets/129fc042-2e42-41ee-a0fd-80c8bd7e3ac9" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
