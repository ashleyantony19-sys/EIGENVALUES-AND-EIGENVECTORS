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
import numpy as np

A = np.array([[2, 1],
              [1, 2]])

value, vector = np.linalg.eig(A)

print("Eigenvalues:")
print(value)

print("Eigenvectors:")
print(vector)
```
## Output:

<img width="763" height="480" alt="Screenshot 2026-05-11 191430" src="https://github.com/user-attachments/assets/f2a07421-6faa-4756-b86c-1f3ed18592d7" />







<img width="681" height="379" alt="Screenshot 2026-05-11 191435" src="https://github.com/user-attachments/assets/bcb984dc-a5b8-450c-b4c6-1e9fa4c664f6" />





## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
