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
# Register No:212225230055
# Developed By:dharshansri
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
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
<br>
<br>
<br>
<img width="1291" height="648" alt="Screenshot 2026-02-07 090242" src="https://github.com/user-attachments/assets/1a24b118-c4f8-4c03-a74e-5644d0101f69" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1267" height="748" alt="Screenshot 2026-02-07 090302" src="https://github.com/user-attachments/assets/bc7e1503-48a0-4f44-9735-eec63389fe0e" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1230" height="656" alt="Screenshot 2026-02-07 090333" src="https://github.com/user-attachments/assets/ea6c10da-cfcf-495d-be21-0977408630da" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
