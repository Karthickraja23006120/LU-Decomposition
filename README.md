# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Program 1
1. import numpy
2. import lu from the linear algebra fromscipy
3. get the input array 
4. use lu function and assign in p,l,u
5. print the l and u matrix 
## Program 2
1. import numpy
2. import linear algebra from scipy to solve the factor
3. get the input for both the arrays
4. solve the l and u matrix 
5. assign its factor to a x
6. print x
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Karthick Raja K
RegisterNumber: 23006120
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Karthick Raja K
RegisterNumber: 23006120
*/
import numpy as np
from scipy linalg.import lu
p,l,u=lu(a)
print(l)
print(u)

```

## Output:
![lu decomposition](/Screenshot%202023-07-31%20182759.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

