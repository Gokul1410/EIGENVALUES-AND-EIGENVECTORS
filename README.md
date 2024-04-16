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
#Developed by: Gokul C
#RegisterNumber:212223240040
import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigval,eigvect=np.linalg.eig(matrix)
print("Eigen values are",eigval,"and Eigen Vectors are",eigvect)
## Output:
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
```
## Output:

![Screenshot 2024-04-16 174651](https://github.com/Gokul1410/EIGENVALUES-AND-EIGENVECTORS/assets/153058321/3abb7c4c-03ba-4866-a709-43cae1e34814)
![Screenshot 2024-04-16 174703](https://github.com/Gokul1410/EIGENVALUES-AND-EIGENVECTORS/assets/153058321/07487f3c-3630-479e-bbbd-72118a56114c)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
