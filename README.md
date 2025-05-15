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
# Register No:212224220075
# Developed By:Raghu Ram V R
# 1-Norm of a Matrix
```
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)
```


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: V.R.Raghu Ram
RegisterNumber: 212224220075
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")


# Infinity Norm of a Matrix

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(f"{result:.2f}")



```
## Output:
### 1-Norm of a Matrix
![alt text](<Screenshot (63).png>)


### 2-Norm of a Matrix

![alt text](<Screenshot (64).png>)

### Infinity Norm of a Matrix

![alt text](<Screenshot (65).png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
