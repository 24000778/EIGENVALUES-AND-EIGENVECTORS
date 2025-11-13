# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library using 'import numpy as np'.
### Step 2: Define the matrix using np.array().
### Step 3: Using np.linalg.eig(), compute the eigenvalues and eigenvectors.
### Step 4: Display the eigenvalues and eigenvectors using print().

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:G.Sindhu Priya Reddy 
#RegisterNumber:212224040319

import numpy as np
a = np.array([[4,2], [2,4]])
eig_value,eig_vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_value,eig_vector))

```
## Output:

<img width="1251" height="771" alt="Screenshot 2025-09-16 191336" src="https://github.com/user-attachments/assets/34f8b202-0d92-428e-b5aa-9dffca94d606" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
