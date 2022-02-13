# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a matrix

## ALGORITHM:
### Step 1:
use impory as np
### Step 2:
enter the input
### Step 3:
use for loop and range
### Step 4:
use np.linalg.inv() to find the inverse of a matrix
### Step 5:
print()


## PROGRAM:
```
import numpy as np
l1,l2=[],[]
n1,n2=int(input()),int(input())
for i in range(n1):
    for j in range(n2):
        values=int(input())
        l1.append(values)
    l2.append(l1)
    l1=[]
print(l2)
inverse=np.linalg.inv(l2)
print(inverse)
```
## OUTPUT:
![output](00.png)
## RESULT:
Thus the aove program is executed successfully.