# Implementation of Univariate Linear Regression
## AIM:
To implement univariate Linear Regression to fit a straight line using least squares.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Get the independent variable X and dependent variable Y.
2. Calculate the mean of the X -values and the mean of the Y -values.
3. Find the slope m of the line of best fit using the formula. 
<img width="231" alt="image" src="https://user-images.githubusercontent.com/93026020/192078527-b3b5ee3e-992f-46c4-865b-3b7ce4ac54ad.png">
4. Compute the y -intercept of the line by using the formula:
<img width="148" alt="image" src="https://user-images.githubusercontent.com/93026020/192078545-79d70b90-7e9d-4b85-9f8b-9d7548a4c5a4.png">
5. Use the slope m and the y -intercept to form the equation of the line.
6. Obtain the straight line equation Y=mX+b and plot the scatterplot.

## Program:
```

import
numpy as np
import
matplotlib.pyplot as plt
X 2, 3, 4, 51)
Y 4, 5, 4, 51)
= np.mean(x)
x mean
= np.mean(Y)
Y_mean
np. - x_mean) • (Y - y_mean))
numerator
denominator
- x_mean) 2)
m numerator/denominator
b = y_mean - m • x_mean
print("S10pe (m):" , m)
print("lntercept (b):" ,
b)
Y_pred = m * X + b
print("Va1ue:", Y_pred)
x input("Enter value: "
YY = m float(x) + b
print("Va1ue:", yy)
# Plotting
pit. scatter(X, Y, label-"Data Points")
plt.p10t(X, Y_pred, Fit Line")
plt.xlabel( "X")
plt .ylabel( "Y" )
plt. legend ( )
plt.title( "Univariate Linear Regression")
plt. show()

Developed by: Selshiya F
RegisterNumber: 212224060241

```

## Output:

<img width="1142" height="722" alt="image" src="https://github.com/user-attachments/assets/cbb217a0-3b72-4fbc-b2e8-6051bae38f84" />

## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
