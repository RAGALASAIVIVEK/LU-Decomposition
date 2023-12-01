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
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: sai vivek ragala
RegisterNumber: 23003676
'''
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
'''Program to solve a matrix using LU decomposition.
Developed by: sai vivek ragala
RegisterNumber: 23003676
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![maths 2a 1](https://github.com/RAGALASAIVIVEK/LU-Decomposition/assets/144979718/884e5441-8b81-41f2-8ae7-04cfaf79dc6f)

![maths 2a 2](https://github.com/RAGALASAIVIVEK/LU-Decomposition/assets/144979718/533a059d-f4b9-4b46-b9c7-5032ae96b961)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

