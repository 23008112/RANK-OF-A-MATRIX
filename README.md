# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy model to use the builtin function for calculation
### Step 2:
Prepare the lists from the given two dimension matrix and assign in np.array() 
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: R.Sanjana
#RegisterNumber:23008112
import numpy as np
a=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
sol=np.linalg.matrix_rank(a)
print(sol)
```
## Output:
![Alt text](<Screenshot 2023-12-23 113353.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

