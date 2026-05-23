# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy library.
### Step 2: Create and store the matrix using a NumPy array.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of the matrix.
## Program:
```
#Program to find the rank of a matrix.
#Developed by:V.Lakshita Rai 
#RegisterNumber:212225220055
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

matrix = np.array([[1, 2, 3],
                   [3, 6, 9]])

rank = np.linalg.matrix_rank(matrix)

print(rank)
```
## Output:
<img width="652" height="281" alt="image" src="https://github.com/user-attachments/assets/cb59e605-7650-4e56-b8ca-a95bcce90ac3" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

