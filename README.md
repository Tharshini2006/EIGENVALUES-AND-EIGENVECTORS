# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
```
import numpy as np
a= np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## Output:
![Screenshot 2024-11-30 232643](https://github.com/user-attachments/assets/e8323412-dbe8-4891-8104-3dca55cef002)
![Screenshot 2024-11-30 232659](https://github.com/user-attachments/assets/8b1112ab-d8b0-42f8-b851-d8fbf62ee192)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
