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
#Developed by: VINNUSHKUMAR L S
#RegisterNumber:23012349
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
result=np.linalg.solve(A,B)
print(result)
```
## Output:
![solution to system of linear equation](https://github.com/vinnush147/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/147139234/50d5de0b-df59-4da5-b6d0-75796ca3b92e)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

