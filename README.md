# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
Import numoy package
2. 
From scipy package import lu
3. 
Get input from the user
4. 
Print result
## Program:
```PYTHON
'''Program to find L and U matrix using LU decomposition.
Developed by: Gayathri A
RegisterNumber: 21500440
'''

# To print L and U matrix
import numpy as np
import scipy
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
![output](./IMAGE.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

