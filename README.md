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
#Program to find the solution for the given linear equations
#Developed by: A.VIJIYALAKSHMI
#RegisterNumber: 25017569
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
x=np.linalg.solve(A,B)
print(x)
```
## Output:
<img width="720" height="353" alt="Screenshot 2025-11-19 104359" src="https://github.com/user-attachments/assets/ad4bf6d9-80d2-4deb-a6f2-697b2448521a" />

<img width="342" height="159" alt="Screenshot 2025-11-19 104433" src="https://github.com/user-attachments/assets/00ebd275-2563-4711-8844-79107b7f5806" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

