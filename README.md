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
#Developed by: santhosh.G
#RegisterNumber:25016754
import numpy as np
a=np.array([[1,-3],[3,1]])
b=np.array([0,10])
x=np.linalg.solve(a,b)
print(x)
```
<img width="1286" height="759" alt="Screenshot 2025-11-19 104417" src="https://github.com/user-attachments/assets/7c57727f-4b03-455c-be21-af4641a418f6" />

## Output:
<img width="1281" height="204" alt="Screenshot 2025-11-19 104514" src="https://github.com/user-attachments/assets/c50e2a0b-73f6-42a2-81fe-c88d8f5b3ffe" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

