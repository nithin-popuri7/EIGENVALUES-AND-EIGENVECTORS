# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import numpy as np.
### Step 2: 
Give the values of the matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the Eigen value and Eigen vectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Popuri Siva Naga Nithin
#RegisterNumber:21003942
import numpy as np
a=([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![github logo](img3.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
