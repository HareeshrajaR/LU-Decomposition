## DATE:
## EXN0:05 LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

### Program:
## (i) To find the L and U matrix
## Program to find L and U matrix using LU decomposition.
## Developed by: HAREESH R
## RegisterNumber: 212223230068
```

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
## (ii) To find the LU Decomposition of a matrix

## Program to solve a matrix using LU decomposition.
## Developed by: HAREESH R
## RegisterNumber: 212223230068


```

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output 01:

![Screenshot 2024-09-25 114901](https://github.com/user-attachments/assets/aebbbbfe-09ab-4b87-be24-40050f75d1a8)


## Output 02:
![Screenshot 2024-09-25 114734](https://github.com/user-attachments/assets/04a34d18-c84b-43c6-8d61-c3b12feedb9a)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

