# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import pandas.

### Step2
Import linear model from sklearn

### Step3
Read the files cars.csv

### Step4
Assign the values for x and y as requried.

### Step5
Create the LinearRegression model and predict the output

## Program:
```
Developed by : M.Hashwatha
RegisterNumber : 23012398

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1) (2).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))

```
## Output:

![image](https://github.com/Hashwatha/Multivariate-Linear-Regression/assets/150231431/c77bf4ba-6cd0-4c9f-ab49-afcb695ad67c)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
