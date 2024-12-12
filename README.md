# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
step1:Define the package as scipy.linalg import lu.
step2:Get input from user and print L and U matrix by 'print' .
step3:Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
step4:print the variable 'X'.
```

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by:shravani.m 
RegisterNumber:24006268 
```
```
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```

(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: shravani.m
RegisterNumber:24006268 
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```
## Output:
![Screenshot 2024-12-12 182048](https://github.com/user-attachments/assets/d1e0b139-057f-4f7c-9a84-4ca2c3d5f2cb)
![Screenshot 2024-12-12 182745](https://github.com/user-attachments/assets/968e2a07-cc33-4567-a79f-9dc3fc4b10ac)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

