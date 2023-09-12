# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import the required libraries and read the dataframe.
2. Assign hours to X and scores to Y.
3. Implement training set and test set of the data frame.
4. Plot the required graph both for test data and training data.
5. Find the values of MSE,MAE and RMSE.

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: SYED ADIL BASHA
RegisterNumber:  212221043008

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.metrics import mean_absolute_error,mean_squared_error
df=pd.read_csv('/student_scores.csv')
df.head()
df.tail()

X=df.iloc[:,:-1].values
X

Y=df.iloc[:,1].values
Y

Y_pred

Y_test

#Graph plot for training data
plt.scatter(X_train,Y_train,color="orange")
plt.plot(X_train,regressor.predict(X_train),color="red")
plt.title("Hours vs Scores (Training Set)")
plt.xlabel("Hours")
plt.ylabel("Scores")
plt.show()

#Graph plot for test data
plt.scatter(X_test,Y_test,color="purple")
plt.plot(X_test,regressor.predict(X_test),color="yellow")
plt.title("Hours vs Scores (Test Set)")
plt.xlabel("Hours")
plt.ylabel("Scores")
plt.show()
mse=mean_squared_error(Y_test,Y_pred)
print('MSE=',mse)
mae=mean_absolute_error(Y_test,Y_pred)
print('MAE=',mae)
rmse=np.sqrt(mse)
print('RMSE=',rmse)


*/
```

## Output:
## 1.df.head()
![Screenshot (80)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/66639be4-684b-4fe8-836f-5343fdbc5644)

## 2.df.tail()
![Screenshot (81)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/8c92c05c-5a6a-4057-bf64-b700ef0689a9)

## 3.Array value of X
![Screenshot (82)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/1e4b25ac-1a7a-4814-8330-91660dcec5f0)

## 4.Array value of Y
![Screenshot (83)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/37ff425f-7836-482e-8057-b0f547a673db)

## 5.Values of Y prediction
![Screenshot (84)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/20ad45a6-cea2-47f7-b8eb-09ad826b79fd)

## 6.Array values of Y test
![Screenshot (85)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/903624d7-f181-4486-857b-7e6ce2c0adab)

## 7.Training Set Graph
![Screenshot (86)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/d18a9d87-1b32-4213-8c2c-9361437a962a

## 8.Test Set Graph
![Screenshot (87)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/178a0cd7-1a15-4235-857f-5d4f190cc41c)

## 9.Values of MSE,MAE and RMSE
![Screenshot (88)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/aa93d408-cffb-4017-8fe6-838640b08aff)
![Screenshot (89)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/2f7a57e0-5ae8-4daa-ac37-5315cbb210af)
![Screenshot (90)](https://github.com/SYEDADILBASHA1/Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored/assets/134796157/265dfb5b-deea-4160-ba4e-72e122b5b642)



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
