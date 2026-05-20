# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:Import the numpy module to use the built-in functions for calculation

## Step 2:Prepare the lists from matrix and assign in np.array()

## Step 3:Using the np.linalg.solve(), we can find the solutions.

## Step 4:End the program
## Program:
(i) To find the L and U matrix

'''
Program to find the L and U matrix.
Developed by: Aadhithya.V
RegisterNumber: 212225040002
'''
import os  
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
from scipy.linalg import lu 
A=np.array(eval(input()))
P,L,U=lu(A) 
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix
#Program to solve a matrix using LU decomposition.
#Developed by: Aadhithya v
#RegisterNumber: 212225040002


# To print X matrix (solution to the equations)
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

## Output:
<img width="1233" height="727" alt="Screenshot 2026-05-20 092446" src="https://github.com/user-attachments/assets/a6895770-afe0-4e1d-b8e3-f42e253303aa" />
<img width="1224" height="582" alt="Screenshot 2026-05-20 092508" src="https://github.com/user-attachments/assets/41d70733-7201-4964-a141-b498749943ec" />

<img width="1227" height="722" alt="Screenshot 2026-05-20 092530" src="https://github.com/user-attachments/assets/f54d5d90-8f59-4484-b576-7c7ad88be7f8" />

<img width="1223" height="314" alt="Screenshot 2026-05-20 092541" src="https://github.com/user-attachments/assets/70459267-b0a3-469c-b197-5a391d616874" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

