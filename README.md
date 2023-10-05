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
# Register No:212222230116
# Developed By:Ranjan K

# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
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
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-10-05 202503](https://github.com/Ranjanranjan/Norm-of-a-matrix/assets/130027697/e042bfbc-ee80-4919-80dc-e931dbfd9129)




### 2-Norm of a Matrix

![Screenshot 2023-10-05 202547](https://github.com/Ranjanranjan/Norm-of-a-matrix/assets/130027697/56eb8136-df0a-477b-9b60-cc9e1066d6ed)


### Infinity Norm of a Matrix
![Screenshot 2023-10-05 202559](https://github.com/Ranjanranjan/Norm-of-a-matrix/assets/130027697/8c65ad84-662d-453d-8cda-f05a605c3e5d)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
