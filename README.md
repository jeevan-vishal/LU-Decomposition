# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy
2. from linalg import lu
3. get input as array
4. create variables of lu of input
5. print l and u

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Jeevan Vishal GD 
RegisterNumber: 212224240062

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Jeevan Vishal GD
RegisterNumber: 212224240062


import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)

```

## Output:
![Screenshot 2025-03-21 145037](https://github.com/user-attachments/assets/77e67c01-4065-4d9b-aa80-af7c644c7081)
![Screenshot 2025-03-21 145049](https://github.com/user-attachments/assets/e39f1a93-870c-4434-90e1-03446699f551)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

