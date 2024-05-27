# Exp:02 RANK-OF-A-MATRIX
# DATE:09/03/2024
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Importing the NumPy library using the statement import numpy as np.
### Step 2: 
Define a 3x3 matrix A with the specified values.
### Step 3: 
Compute the rank of matrix A using the np.linalg.matrix_rank() function.
### Step 4: 
End the program.
## QUESTION:
```
Write a program to find the rank for the given matrix([5,-3,-10],[2,2,-3],[-3,-1,5]).
```
## Program:
```

Developed by:SAMEENA J 
RegisterNumber:2305002019  

```
`````python
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
`````
## Output:
![Screenshot (57)](https://github.com/sameena77/RANK-OF-A-MATRIX/assets/155620541/0d58fdb5-6404-49b7-9c5e-4a370c29f2c9)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

