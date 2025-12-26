# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:Allabakash A
# Developed By:25004583
# 1-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,1)
print(norm)


# 2-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(norm.round(2))


# Infinity Norm of a Matrix


import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,np.inf)
print(norm)


```
## Output:
### 1-Norm of a Matrix

<img width="1215" height="865" alt="Screenshot 2025-12-26 204451" src="https://github.com/user-attachments/assets/ee8c37ea-367d-4ebd-87f2-3cccf9993e59" />

### 2-Norm of a Matrix
<img width="1198" height="872" alt="Screenshot 2025-12-26 204520" src="https://github.com/user-attachments/assets/fae045b4-a4a1-4dd7-93db-9d0229e059ea" />


### Infinity Norm of a Matrix
<img width="1123" height="879" alt="Screenshot 2025-12-26 204536" src="https://github.com/user-attachments/assets/ed1208ce-e05e-4ba1-ae72-6af81764764b" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
