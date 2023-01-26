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
# Register No:MUKESH.P
# Developed By:22008456
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)




```
## Output:
### 1-Norm of a Matrix
![norm 1 op](https://user-images.githubusercontent.com/119393818/214794730-a4571a22-843b-485b-8057-923a16b174c6.png)

### 2-Norm of a Matrix

![norm 2 op](https://user-images.githubusercontent.com/119393818/214794788-1dce43ff-62fd-4cce-b3fb-605e315def0c.png)

### Infinity Norm of a Matrix

![norm inf op](https://user-images.githubusercontent.com/119393818/214794828-8bb0b1da-644f-48a8-9d33-06297b00f3a1.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
