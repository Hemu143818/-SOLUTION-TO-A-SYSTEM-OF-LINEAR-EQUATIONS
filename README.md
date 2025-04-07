# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
1. Import the NumPy library.
2. Create a 2×2 coefficient matrix A.
3. Create a constant vector B.
4. Solve the system of linear equations 𝐴⋅𝑋=𝐵 A⋅X=B using np.linalg.solve().
5. Round the resulting solution to 6 decimal places using np.round().
6. Print the final solution
## Program:
~~~
import numpy as np

A = np.array([[1, -3], [3, 1]])

B = np.array([0, 10])

solution = np.linalg.solve(A, B)

solution = np.round(solution, decimals=6)

print(solution)
~~~

## Output:
![Screenshot 2025-04-07 094314](https://github.com/user-attachments/assets/b707aeb6-c2bf-4d46-a32c-67ea9a2dc7d0)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

