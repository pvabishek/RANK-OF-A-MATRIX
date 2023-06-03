# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Step 1:
We have imported numpy which is needed.

Step 2:
We have created a matrix by using np.array with different values in it.

Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

Step 4:
Finally, print the value of the rank of the matrix.

## Program:
```
#Program to find the rank of a matrix.
#Developed by: P.V.Abishek
#RegisterNumber:212222230003
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![Screenshot 2023-06-03 123420](https://github.com/pvabishek/RANK-OF-A-MATRIX/assets/119405626/9213d8fc-583a-4ee3-9730-794a10ab7d3d)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

