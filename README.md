# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'
 

## Program:
(i) To find the L and U matrix
```
Developed by: S.HEMAVATHY
RegisterNumber: 212223230076
'''
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: S.HEMAVATHY
RegisterNumber: 212223230076
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)



```

## Output:
![Screenshot 2024-04-06 151539](https://github.com/Hemaatchu/LU-Decomposition/assets/147328300/e5359efb-9b88-4e71-adbc-21b63f47750f)

![Screenshot 2024-04-06 151554](https://github.com/Hemaatchu/LU-Decomposition/assets/147328300/f285ed57-baf3-4b1d-ae3e-dd6b57a35d43)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

