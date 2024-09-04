# EXP-1: SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
#Developed by: Harsshitha lakshamanan
#RegisterNumber: 212223230075
import numpy as np
a = np.array([[5, -3, -10],
              [2, 2, -3],
              [-3, -1, 5]])
b = np.array([-9, 4, -1])
c = np.linalg.solve(a,b)
print(c)
```
## Output:
![image](https://github.com/user-attachments/assets/60ffc33d-36c4-488d-adc4-6a718447286c)
![image](https://github.com/user-attachments/assets/aea73ae3-202c-46ec-b914-d6a68e83d96c)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

