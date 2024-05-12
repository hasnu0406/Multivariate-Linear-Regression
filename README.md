# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import pandas as pd.

### Step2
Use pd.read_csv to find coefficient and intercept.

### Step3
create the program for multivariate linear regression.

### Step4
Run the program and take screen shot.

### Step5
End of the program.

## Program:
```Python
Developed by: HASNA MUBARAK AZEEM
Reg No: 212223240052
import panda as pd
from sklearn import linear_model

df = pd.read_csv("csvfile.csv")

X = df[['Weight, Volume']]
Y = df['CO2']

regr = linear_model.LinearRegression()
regr.fit(X,Y)

print('coefficients:', regr.coef_)
print("Intercept:",regr.coef_)

predictedCO2 = regr.predict([[3300,1300]])
print('predicted CO2 for the corresponding Weight and Volume',predictedCO2)
```
## Output:
![alt text](<MATHS 10.png>)
### Insert your output
![alt text](<MATHS 10 (1).png>)
<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.