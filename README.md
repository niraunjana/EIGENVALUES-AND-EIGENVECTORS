# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2: list the elements in array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the eigen values and eigen vectors
### Step 5: End the program

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by:Niraunjana Gayathri G R
#RegisterNumber:22008369

import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format (values,vectors))
```

## Output:
![OUTPUT](./image/imgex04.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
