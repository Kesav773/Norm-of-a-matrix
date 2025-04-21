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
# Register No: 212224110031
# Developed By:Kesav K M

# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-21 182338](https://github.com/user-attachments/assets/82024f6b-e222-4d87-a4e9-cebd93d45be6)


### 2-Norm of a Matrix
![Screenshot 2025-04-21 182403](https://github.com/user-attachments/assets/8909ee42-fb73-43f4-82cb-237933627b49)


### Infinity Norm of a Matrix
![Screenshot 2025-04-21 182419](https://github.com/user-attachments/assets/09d877e8-f258-4e67-9b42-be401f951d20)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
