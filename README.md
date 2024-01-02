# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1:Get the two values from the user
<br>

### Step2:Assign the value of second variable to a temporary variabl
<br>

### Step3:Assign the value of the first variable to the second variable.
<br>

### Step4:Assign the value in temporary variable to the first variable
<br>

### Step5:Print both the values it would be interchanged
<br>
## Program:
```
#program for Implementation of Multivariate Linear Regression
#developed by: VIGNESH M
#register number:23014020
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars.csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))





```
## Output:
![Screenshot 2024-01-02 221329](https://github.com/vigneshvickyu/Multivariate-Linear-Regression/assets/151948835/bd2a5bad-84cf-4a29-aa00-321160df2e2e)



### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
