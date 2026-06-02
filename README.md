# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Import the NumPy library and create the matrix using np.array().
Step 2: Use np.linalg.inv() function to find the inverse of the matrix.
Step 3: Store the inverse matrix in a variable.
Step 4: Print the inverse matrix using the print() function.


## Program:
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
A = np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
result = np.linalg.inv(A)
print(result)

```
## Output:
<img width="1382" height="850" alt="Screenshot 2026-06-02 133443" src="https://github.com/user-attachments/assets/889df18c-d807-4096-819f-43e24af90fcc" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

