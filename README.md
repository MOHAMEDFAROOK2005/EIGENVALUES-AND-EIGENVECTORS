# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculations.
### Step 2: Prepare the list from the given matrix and assign in np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: END PROGRAM

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:MOHAMED FAROOK S
#RegisterNumber:23014058
import numpy as np
a=[[4,2],[2,4]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![image](https://github.com/MOHAMEDFAROOK2005/EIGENVALUES-AND-EIGENVECTORS/assets/150319482/ae7f5120-3c4d-428b-806a-d2e6e31bb805)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
