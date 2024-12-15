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
```
# Register No: 24900222
# Developed By: manoj.r
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}". format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans =np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-15 211832](https://github.com/user-attachments/assets/3d8b76ff-d286-4719-8669-b093f4c4e1e7)

### 2-Norm of a Matrix
![Screenshot 2024-12-15 211846](https://github.com/user-attachments/assets/ebb1dd16-0e51-4818-b08f-65874abedec0)


### Infinity Norm of a Matrix
![Screenshot 2024-12-15 211859](https://github.com/user-attachments/assets/7971a3dc-c329-4116-b88d-6fa4c6255f5c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
