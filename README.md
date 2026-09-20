# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program and import the required library (numpy).
2.Initialize the matrix for which the LU decomposition needs to be found.
3.Apply LU Decomposition
4.Display the results

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: K.sundar
RegisterNumber: 212225040438
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:K.sundar
RegisterNumber: 212225040438

# To print X matrix (solution to the equations)
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)


*/
```

## Output:
<img width="1240" height="476" alt="Screenshot 2026-09-20 113311" src="https://github.com/user-attachments/assets/b331335c-07c4-49be-895f-763e62d3c05b" />

<img width="1230" height="228" alt="Screenshot 2026-09-20 113413" src="https://github.com/user-attachments/assets/85efc3bc-6d9c-4b51-a749-6a82dcf2cdcc" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

