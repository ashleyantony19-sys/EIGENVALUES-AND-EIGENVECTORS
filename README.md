# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2:  Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: ASHLEY ANTONY
#RegisterNumber: 212225220013
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evalu,evect=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(evalu,evect))
```
## Output:

<img width="1043" height="289" alt="WhatsApp Image 2026-06-01 at 9 35 23 AM" src="https://github.com/user-attachments/assets/b5030874-7346-4bd5-b8db-f0a58be43f88" />



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
