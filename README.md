# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' . 
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable 
4. print the variable 'X'

## Program:
```
(i) To find the L and U matrix

Program to find the L and U matrix.
Developed by: STEPHEN RAJ.Y
RegisterNumber:212223230217

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix

Program to find the LU Decomposition of a matrix.
Developed by: STEPHEN RAJ.Y
RegisterNumber: 212223230217
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
![lu decomposition]()
(i) To find the L and U matrix

![Screenshot 2024-04-05 154738](https://github.com/23002248/LU-Decomposition/assets/151701774/542eebe9-544f-428f-b797-f987e78986ee)

(ii) To find the LU Decomposition of a matrix
![Screenshot 2024-04-05 154924](https://github.com/23002248/LU-Decomposition/assets/151701774/61fa3689-1da2-4ee2-b134-14313f87713e)






## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

