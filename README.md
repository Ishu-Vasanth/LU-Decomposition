# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library using import statement. 
2. From scipy package import lu().
3. Get input from user and pass it as an array.
4. Get P, L U martix using lu().
5. print L and U matrix. 

## Program:
```
/*
Program to find L and U matrix using LU decomposition.
Developed by: ishwarya.v
RegisterNumber: 21002894
*/  
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P, L, U=lu(A)
print(L)
print(U)
```
## Output:
![lu decomposition](lu.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

