# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
to find eigenvalues by solving the characterstics equation
### Step 2: 
for each eigenvalues solve the system of linear equations to find the corresponded eigenvectors
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
confirm that for each eigenvalue - eigenvectors pair

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: YENUGANTI PRATHYUSHA 
#RegisterNumber:23009045
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/prathyusharavi/EIGENVALUES-AND-EIGENVECTORS/assets/147474424/eaa524ef-9426-438a-a936-7d4c8dafe20b)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
