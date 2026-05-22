# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
import numpy as np
X = np.array(eval(input()))
Y = np.array(eval(input()))
X_mean = np.mean(X)
Y_mean = np.mean(Y)
num = 0
den = 0
for i in range(len(X)):
    num += (X[i] - X_mean) * (Y[i] - Y_mean)
    den += (X[i] - X_mean) ** 2
m = num / den
c = Y_mean - m * X_mean
print(m, c)
Y_pred = m * X + c
print(Y_pred)
```
## Output:
<img width="365" height="98" alt="image" src="https://github.com/user-attachments/assets/ce6f8f63-914d-41e3-9dc9-49c279bdf6c4" />

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
