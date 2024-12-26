# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm for Program 1:

1. Import numpy and scipy.linalg, in linalg you can input lu. and in second program can import lu factor and lu solve from python library as same as in second program.

2. Get the input from user as the form of nested list to compute numpy array format.

3. Use inputted array (matrix) to compute in corresponding builtin modules function such as lu and create new variables such as piv, matrixu matrix to store the result.

4. Print the corresponding bvariable to get output (matrix)

5. Print the corresponding bvariable to get output (u matrix)

## Algorithm for program 2:

1. In second program can import lu_factor and lu solve from python library as same as in second program.

2. Get the input from user in the form of nested list to compute numpy array format and declare it for both the variables

3. Create the variable to Use inputted array to compute of lu factor of matrix varaible.

4. Create the new variable for lu solve to compute of variable and 'b' variable

5. Print the corresponding variable (solution) to get the output.

## Program1:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:KATHIRESH M
RegisterNumber:24901022
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:KATHIRESH M
RegisterNumber: 24901022
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```


## Output:
![Output1](OUTPUT1.png)
![Output2](OUTPUT2.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

