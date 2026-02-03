# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the NumPy library using the import numpy as np statement.
### Step 2: 
Define the given matrix using the np.array() function.
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
Display the rank of the matrix using the print() function. 
## Program:
```#Program to find the rank of a matrix.
#Developed by: SWATHI S
#RegisterNumber: 25016151
import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![alt text](<Screenshot 2026-02-03 091833.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

