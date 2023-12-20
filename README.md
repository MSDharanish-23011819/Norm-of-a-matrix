# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```
# Register No: 23011819
# Developed By: MS Dharanish
# 1-Norm of a Matrix :
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))




# 2-Norm of a Matrix :

#Program to find 2-norm of a matrix.
#Developed by: MS Dharanish
#RegisterNumber:212223240027
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))




# Infinity Norm of a Matrix :
#Python program to find the infinity of a matrix and display the result
#Developed by: MS Dharanish
#RegisterNumber:212223240027
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-20 201223](https://github.com/MSDharanish-23011819/Norm-of-a-matrix/assets/147139454/23325584-88a9-4f07-8e68-b2de51b4aed8)

### 2-Norm of a Matrix
![Screenshot 2023-12-20 201313](https://github.com/MSDharanish-23011819/Norm-of-a-matrix/assets/147139454/d8d10b5e-326a-4f70-a491-aa861ccecfe0)

### Infinity Norm of a Matrix
![Screenshot 2023-12-20 201426](https://github.com/MSDharanish-23011819/Norm-of-a-matrix/assets/147139454/ba7541fd-8725-49ad-99d7-fc929dc9a717)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
