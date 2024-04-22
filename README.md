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
# Register No:212223240050
# Developed By:Harshini Y
# 1-Norm of a Matrix
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))



# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
infinity_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(infinity_matrix))


```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/harshiniyu/Norm-of-a-matrix/assets/144979786/7f9e0bc0-decb-46e5-a25f-ad8132acbcf7)

### 2-Norm of a Matrix

![image](https://github.com/harshiniyu/Norm-of-a-matrix/assets/144979786/ed6baa25-09d3-4b1b-af4d-fd50c26b58e8)

### Infinity Norm of a Matrix

![image](https://github.com/harshiniyu/Norm-of-a-matrix/assets/144979786/4436c566-d9e4-41a9-ad9a-ddd85a01bea7)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
