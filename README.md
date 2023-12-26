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
# Register No:23004520
# Developed By:Vedagiri Indu sree
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Vedagiri Indu sree
RegisterNumber: 23004520
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
## Output:
### 1-Norm of a Matrix
![image](https://github.com/vedagiriindusree/Norm-of-a-matrix/assets/149366776/466fee6d-e9aa-4de7-9882-de0b7c49f608)

### 2-Norm of a Matrix
![image](https://github.com/vedagiriindusree/Norm-of-a-matrix/assets/149366776/f52a1f7f-048e-4c27-95e7-a053f47c16c8)

### Infinity Norm of a Matrix
![image](https://github.com/vedagiriindusree/Norm-of-a-matrix/assets/149366776/fa83091f-8cc6-4eca-a5ec-0101ab05eb4d)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
