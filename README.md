# Multiplying-two-matrix

## AIM:
To write a python program to multiply two matrices.
## ALGORITHM:

### Step 1:
Import numpy as np
### Step 2:
Create 2 empty files
### Step 3:
Get the input from the user
### Step 4:
Create a nested for-loop and append the values.
### Step 5:
Store the values in a separate variable.Multiply the values.
## PROGRAM: 
import numpy as np
l1, l2 = [],[]
n= int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
val1= np.array(l1)
val2 = np.array(l2)
result = val1*val2
print("Product of two arrays is:",result)
## OUTPUT:
![pic1](https://user-images.githubusercontent.com/94386222/153753558-a5e28bea-1873-4bf7-acfb-d3e4721c5f6d.png)

## RESULT:

