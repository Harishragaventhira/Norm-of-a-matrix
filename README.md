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
# Register No:harish
# Developed By:23013571
# 1-Norm of a Matriximport numpy as np
array=([[-1,3],[3,4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
array1=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Harishragaventhira/Norm-of-a-matrix/assets/145548269/c8cd2b60-3dae-42ab-bc02-0b220c9729a6)
### 2-Norm of a Matrix
![image](https://github.com/Harishragaventhira/Norm-of-a-matrix/assets/145548269/e0f58c18-e285-49c8-9825-ceb033b72143)
### Infinity Norm of a Matrix
![image](https://github.com/Harishragaventhira/Norm-of-a-matrix/assets/145548269/85c259d9-dc03-49f3-8cc5-8428092b22be)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
