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
# Register No: 23013460
# Developed By: TAMIZHSELVAN B
# 1-Norm of a Matrix
import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,1)
norm="{:.2f}".format(sol)
print(norm)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname:TAMIZHSELVAN B
RegisterNumber: 23013460
'''
import numpy as np
a=([[1,2],[3,4]])
b=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,2)
norm = "{:.2f}".format(sol)
print(norm)

# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname:TAMIZHSELVAN B
RegisterNumber: 23013460
'''
import numpy as np
b=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(sol)
print(norm)

```
## Output:
### 1-Norm of a Matrix

![NORM Output 1](https://github.com/tamizhselvan23013460/Norm-of-a-matrix/assets/150231370/c8ee9c0d-6d75-4544-a46b-a65b9fc2aadf)

### 2-Norm of a Matrix

![NORM Output 2](https://github.com/tamizhselvan23013460/Norm-of-a-matrix/assets/150231370/35d797f8-84ff-44f0-816a-a5007dfe86a7)

### Infinity Norm of a Matrix

![NORM Output 3](https://github.com/tamizhselvan23013460/Norm-of-a-matrix/assets/150231370/0b1a7825-d240-49e3-b8ef-eb21a0bad11a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
