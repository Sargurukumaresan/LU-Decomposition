# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. From Scipy package import lu
3. get input from the user
4. print result

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: SARGURU K
RegisterNumber: 22002828

import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: SARGURU K
RegisterNumber: 22002828

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)

```

## Output:
L and U matrix

![L and U matrix](./L%20and%20U%20matrix.png)

LU decomposition

![LUdecomposition](./LU%20decomposition.png)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

