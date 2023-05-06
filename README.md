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
# 1-Norm of a Matrix

'''
Developed by: PERARASU M
RegisterNumber: 212222100033
'''

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: PERARASU M
RegisterNumber: 212222100033
'''
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix

'''

Developed by: PERARASU M
RegisterNumber: 212222100033
'''
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix

![1](https://user-images.githubusercontent.com/118348589/236612231-0fe77615-fce6-4974-9e90-61413745d2ce.png)


### 2-Norm of a Matrix

![2](https://user-images.githubusercontent.com/118348589/236612242-0332231d-6c03-4d15-8653-95b9004235af.png)


### Infinity Norm of a Matrix

![3](https://user-images.githubusercontent.com/118348589/236612252-4a4587c4-fb05-4fb9-bae0-b4cf7cdd4e1b.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
