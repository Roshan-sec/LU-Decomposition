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
Program to find the L and U matrix.
Developed by: Roshan.P
RegisterNumber:25003567
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

*/
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Roshan.P
RegisterNumber:25003567
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu,pivot=lu_factor(a)
x = lu_solve((lu,pivot), b)
print(x)
```

## Output:
<img width="1178" height="435" alt="image" src="https://github.com/user-attachments/assets/202605b5-ed01-4bb3-b9fb-5af23d375940" />

<img width="861" height="195" alt="image" src="https://github.com/user-attachments/assets/d56973f6-e99f-4d9e-96c7-693e7f629891" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

