# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using np.linalg.inv(),we can find the inverse of a matrix

Step 4:
End the program 

## Program:
import numpy as np

A = np.array([[1, 0, 3],
              [-1, 2, -2],
              [2, 3, -1]])

A_inv = np.linalg.inv(A)

print("Inverse of the matrix:\n", A_inv)

## Output:
<img width="1872" height="972" alt="Screenshot 2026-05-20 142322" src="https://github.com/user-attachments/assets/13bd84bd-25b7-461c-b94c-af3e87d62705" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

