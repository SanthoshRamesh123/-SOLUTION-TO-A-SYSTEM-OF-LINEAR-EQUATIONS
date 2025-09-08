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
```python
#Program to find the solution for the given linear equations.
#Developed by: SANTHOSH R
#RegisterNumber:212224230249

import numpy as np
A = [[5, -3, -10], [2, 2, -3], [-3, -1, 5]]
B = np.array([-9, 4, -1])
C = np.linalg.solve(A,B)
print(C)
```
## Output:

<img width="1310" height="897" alt="Screenshot 2025-09-08 091326" src="https://github.com/user-attachments/assets/0f849c8b-ae15-4efc-849a-7ee88fe3503d" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

