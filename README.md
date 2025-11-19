# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
Write a program to find a solution to a system of linear equations x+3y=5, 2x+5y=-3

#Program to find the solution for the given linear equations.
#Developed by: Abdul Rahim .M
#RegisterNumber: 25015778

import numpy as np

A = np.array([[1, 3],
              [2, 5]])

B = np.array([5, -3])

X = np.linalg.solve(A, B)

print(X)
```
## Output:
<img width="1489" height="736" alt="image" src="https://github.com/user-attachments/assets/8559f422-d3c3-4604-89e9-c0cc6fb0e748" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

