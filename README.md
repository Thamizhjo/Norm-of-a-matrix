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
# Register No:Thamizh kumaran P S
# Developed By:23004070
1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)
2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))
Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Thamizhjo/Norm-of-a-matrix/assets/123891476/c05c8b2c-1f86-4cf8-b99b-7f93fe6a9f7d)


### 2-Norm of a Matrix
![image](https://github.com/Thamizhjo/Norm-of-a-matrix/assets/123891476/e71fc9a4-9c22-4c16-b8f4-6e730fe519b7)


### Infinity Norm of a Matrix
![image](https://github.com/Thamizhjo/Norm-of-a-matrix/assets/123891476/6f077ab0-80a8-489d-aa1a-5ad9c9732b0f)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
