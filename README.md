# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy
### Step 2: Assign the array values
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the values
### step 5: End the program
## Program:
```
Developed by:K.M.Swetha
Register number : 21500844
import numpy as np
a=np.array([[2,2],[1,3]])
values,vector=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vector)
```
## Output:
![image](https://user-images.githubusercontent.com/94228215/154508580-e0bf7fb2-19d9-4fe5-abe5-b0b33b1360f6.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
