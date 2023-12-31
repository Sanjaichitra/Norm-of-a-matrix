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
# Register No:212223230185
# Developed By:SANJAI S
# 1-Norm of a Matrix

~~~
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_martix = "{:.2f}".format(ans)
print(Norm_of_martix)
~~~

# 2-Norm of a Matrix

~~~
import numpy as np

# Type your code here

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_martix = "{:.2f}".format(ans)
print(Norm_of_martix)

~~~

# Infinity Norm of a Matrix

~~~
import numpy as np


mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_martix = "{:.2f}".format(ans)
print(Norm_of_martix)

~~~


## Output:
# 1-Norm of a Matrix
![Screenshot 2023-12-31 195436](https://github.com/Sanjaichitra/Norm-of-a-matrix/assets/144870518/8fc6e792-efb3-4eeb-bd1a-8c40b80d3fdb)

# 2-Norm of a Matrix
![Screenshot 2023-12-31 195520](https://github.com/Sanjaichitra/Norm-of-a-matrix/assets/144870518/f1894c51-fcff-48a4-a136-3b708e61dc5f)


# Infinity Norm of a Matrix
![Screenshot 2023-12-31 195542](https://github.com/Sanjaichitra/Norm-of-a-matrix/assets/144870518/17a6a56e-2397-4954-9fcc-a02a20491191)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
