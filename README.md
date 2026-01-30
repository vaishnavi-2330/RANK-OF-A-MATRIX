# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipments required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.solve(), we can find the solutions.

### Step 4:
End the program

## Program:
```python
#Program to find the rank of a matrix.
#Developed by: Vaishnavi T
#RegisterNumber: 212225100057
#The number of linearly independent rows or columns in a matrix is known as its rank
import numpy as np
A = [[1,2,3],[3,6,9]]
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:

<img width="1473" height="910" alt="Screenshot 2026-01-30 161442" src="https://github.com/user-attachments/assets/43b25fb2-d906-4835-b2f6-649368b2324a" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

