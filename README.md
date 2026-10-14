# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### 5(a)
### Step 1. Import numpy for multi-dimensional array operations
### Step 2. Bring lu from scipy.linalg to handle the actual matrix decomposition
### Step 3. Call the lu(A) function. This splits the target matrix into three seperate output matrices P,L and U
### Step 4. End the program
### 5(b)
### Step 1. Import numpy for multi-dimensional array operations
### Step 2. Bring lu from scipy.linalg to handle the actual matrix decomposition
### Step 3. Pass the factorized components (lu,p) along with the right-hand side matrix b into the lu_solve() functin to compute the solution matrix x
### Step 4. End the program

## Program:
### (i) 5(a) To find the L and U matrix
### Program to find L and U matrix using LU decomposition.
### Developed by: Gogulasharvathan M
### RegisterNumber: 26017320
### import os
### os.environ["OPENBLAS_NUM_THREADS"]= "1"
### import numpy as np
### from scipy.linalg import lu
### A = np.array(eval(input()),dtype=float )
### P,L,U=lu(A)
### print(L)
### print(U)

### (ii) 5(b) To find the LU Decomposition of a matrix
### Program to solve a matrix using LU decomposition.
### Developed by: Gogulasharvathan M
### RegisterNumber: 26017320

### To print X matrix (solution to the equations)
### import os
### os.environ["OPENBLAS_NUM_THREADS"]= "1"
### import numpy as np
### from scipy.linalg import lu_factor,lu_solve

### a = np.array(eval(input()))
### b = np.array(eval(input()))

### l,p = lu_factor(a)
### x = lu_solve((l,p),b)
### print(x)


### Output:
### 5(a):
<img width="1278" height="819" alt="{1CD7341C-849A-4C1C-9277-5D76F5E08CC4}" src="https://github.com/user-attachments/assets/1e9ef0ab-1a49-4366-8ef4-9e2ca99adb31" />

### 5(b):
<img width="1206" height="752" alt="{7A61612B-6CCD-486C-BE08-F801DBEEDFBA}" src="https://github.com/user-attachments/assets/7a893990-a05f-418c-80ee-c7574edee6fe" />




### Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

