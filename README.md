# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Understanding Eigenvalues and Eigenvectors
### Step 2: 
The numpy library's linalg.eig() function is used to compute eigenvalues and eigenvectors

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
Obtaining Eigenvectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: VIJAY R
#RegisterNumber:23013759
import numpy as np
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,Vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))
```

## Output:
![Screenshot 2023-12-24 200007](https://github.com/vijayr21/EIGENVALUES-AND-EIGENVECTORS/assets/149347607/973d6c7a-0e2d-447a-94b8-dda5cfd281a6)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
