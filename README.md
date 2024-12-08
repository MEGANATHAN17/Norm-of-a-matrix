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
# Register No: 24900553
# Developed By: MEGANATHAN R
# 1-Norm of a Matrix
~~~
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
~~~



# 2-Norm of a Matrix
~~~
'''
Program to find 2-norm of a matrix.
Developed by: MEGANATHAN R
RegisterNumber: 24900553
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
~~~




# Infinity Norm of a Matrix
~~~
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
inform="{:.2f}".format(ans)
print(inform)
~~~




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-08 135731](https://github.com/user-attachments/assets/6f138a0b-f2f9-4930-9349-1f33be823a7d)


### 2-Norm of a Matrix
![Screenshot 2024-12-08 135743](https://github.com/user-attachments/assets/8babce15-89bc-46ed-a0bf-c338e817314f)


### Infinity Norm of a Matrix
![Screenshot 2024-12-08 135754](https://github.com/user-attachments/assets/f08b010f-bfe9-491f-a683-78da98d62c55)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
