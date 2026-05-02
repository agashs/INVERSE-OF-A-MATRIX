# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the required library (NumPy) to perform matrix operations.
### Step 2: Define the matrix for which the inverse has to be found.
### Step 3: Use the built-in function to calculate the inverse of the matrix.
### Step 4: Display the inverse matrix as output.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: AGASH S
#RegisterNumber: 212224040014
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
X=np.linalg.inv(A)
print(X)
```
## Output:
<img width="884" height="819" alt="image" src="https://github.com/user-attachments/assets/a0c4f098-ad28-49fd-b9bf-d685c81e7694" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

