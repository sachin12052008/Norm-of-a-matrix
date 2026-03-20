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
# Register No:212225100041
# Developed By:SACHIN J M
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<img width="785" height="219" alt="Screenshot 2026-03-20 224941" src="https://github.com/user-attachments/assets/6001f9d1-ae8d-4009-a869-d66923d25b48" />

### 2-Norm of a Matrix
<img width="635" height="259" alt="Screenshot 2026-03-20 224946" src="https://github.com/user-attachments/assets/d0cb8f47-d7e3-42ff-9ebd-9f124a54a44a" />

# Infinity Norm of a Matrix

<img width="732" height="216" alt="Screenshot 2026-03-20 224953" src="https://github.com/user-attachments/assets/df49b755-3852-4bf6-bc3f-8f1e2dd1a239" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
