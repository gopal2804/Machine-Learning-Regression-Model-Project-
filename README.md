# Machine-Learning-Regression-Model-Project-
## Dataset Description: "Data.csv" 
In the dataset there are total five columns 
* Engine temperature(AT)
* Exhaust vacuum(V)
* Engine pressure(AP)
* Relative humidity(RH)
* Energy output(PE)

All the variables i.e features/independent variables and dependent variable are numerical variable(so no need to perform categorical encoding)
There is no missing data in the dataset
## Problem Statement:
Using the four independent variables <code>AT,V,AP,RH</code> you have to predict the Energy output <code>PE</code>
## Different Regression models used for prediction
* Multiple Linear Regression Model
* Polynomial Regression Model
* Decision Tree Regression Model
* Random Forest Regression Model
## Evaluation metric used for comparison:
Here I have used <code>r2_score</code> metric to compare different models

![image](https://user-images.githubusercontent.com/51901743/172945726-c65d7867-739e-46b1-99a4-c146034a1b0a.png)


## Conclusion
After constructing and comparing all the models we can see that <code>Random Forest Regression Model</code> fits best for the given dataset because its <code>r2_score value is closest to 1</code>
