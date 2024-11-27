# Exp:1 -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
Developed by:Harish Kumar S
RegisterNumber: 24010415
import numpy as np
A = np.array([[1,3],[2,5]])
B = np.array([5,-3])
solution=np.linalg.solve(A,B)
print(solution)
```


## Output:
![Screenshot 2024-11-27 132647](https://github.com/user-attachments/assets/58964423-23c7-4750-8bd6-39474ed74038)
![Screenshot 2024-11-27 132702](https://github.com/user-attachments/assets/e29a4cdb-79ed-4f66-b1a3-757138fee330)






## Result: 
Thus the solutions for the linear equations are successfully solved using python program

