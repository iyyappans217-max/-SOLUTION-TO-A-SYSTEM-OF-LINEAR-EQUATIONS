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

##  Developed by:  IYYAPPAN S 
## reference Number : 25014014
## RegisterNumber:   212225230108

#Program to find the solution for the given linear equations.

import numpy as np
A = [[1,-3],[3,1]]
B = np.array([0,10])
C  = np.linalg.solve(A,B)
print(C)


## Output:

<img width="1326" height="266" alt="image" src="https://github.com/user-attachments/assets/750123cc-6315-4186-914c-f869a38f2d0f" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program..

