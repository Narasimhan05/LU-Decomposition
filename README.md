# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: NARASIMHAN S
RegisterNumber: 212223230133

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: NARASIMHAN S
RegisterNumber: 212223230133

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```
## Output:
![Screenshot 2024-04-17 203632](https://github.com/Narasimhan05/LU-Decomposition/assets/132819871/d24b803e-67a2-461f-b051-007ff0b560d4)

![Screenshot 2024-04-17 203654](https://github.com/Narasimhan05/LU-Decomposition/assets/132819871/3b3537d9-ed1b-4aa5-a823-d6350fd9088b)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

