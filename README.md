# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Gokularamanan k
RegisterNumber: 212222230040
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by:gokularamanan k 
RegisterNumber: 212222230040
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X= lu_solve((lu,piv),B)
print(X
```

## Output:
(i) To find the L and U matrix
![Screenshot (91)](https://github.com/Gokulanbazhagan/LU-Decomposition/assets/119518996/f8633b32-ac46-4ee4-a2de-a4f383360db4)


(ii) To find the LU Decomposition of a matrix
![Screenshot (92)](https://github.com/Gokulanbazhagan/LU-Decomposition/assets/119518996/ae45aaa5-8d38-425e-9a91-05ebba5edca1)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

