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
#Program to find the solution for the given linear equations.

import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
soln=np.linalg.solve(A,B)
print(soln)


#Developed by: SWETHA.S
#RegisterNumber:212222230155
```
## Output:
![image](https://github.com/swethaselvarajm/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/119525603/2175e421-0238-43ac-869c-6110238bddca)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

