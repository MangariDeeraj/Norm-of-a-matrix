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
# Register No:212223100031
# Developed By:MANGARI DEERAJ
```
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
```
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/516a2b28-636c-4bd2-afb7-6c0fb84c0860)

### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/ef4e7291-4c7c-4464-b958-757e64e91b9c)


### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/adaee784-cdc9-438b-9eb6-f14e4ad350a1)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
