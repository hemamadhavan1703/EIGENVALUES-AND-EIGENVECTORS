# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm: Eigenvalues and Eigenvectors
### Step1 : Read the input of the matrix
### Step 2: Create the given square matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the eigenvalues and eigenvectors

## Program:
###
Program to find the eigen values and eigen vectors.
###
Developed by:hema M 
###
RegisterNumber:26018380
###
import os
###
os.environ["OPENBLAS_NUM_THREADS"]="1"
###
import numpy as np 
###
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
###
values,Vectors=np.linalg.eig(a)
###
print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:<img width="1286" height="845" alt="image" src="https://github.com/user-attachments/assets/023c7393-9244-43df-b849-61171d65f50f" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
