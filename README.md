# Credit Card Default Prediction
# **Project Title :Predicting whether a customer will default on his/her credit card**
# **Problem Description**

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments

**Data Description**
**Attribute Information:**

This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:

X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.

X2: Gender (1 = male; 2 = female).

X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).

X4: Marital status (1 = married; 2 = single; 3 = others).

X5: Age (year).

X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows:

X6 = the repayment status in September, 2005;

X7 = the repayment status in August, 2005; . . .;

X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.

X12-X17: Amount of bill statement (NT dollar). 

X12 = amount of bill statement in September, 2005; 

X13 = amount of bill statement in August, 2005; . . .; 

X17 = amount of bill statement in April, 2005.

X18-X23: Amount of previous payment (NT dollar).

X18 = amount paid in September, 2005; 

X19 = amount paid in August, 2005; . . .;

X23 = amount paid in April, 2005.

# **Data Summary:**

**Data Set Name :**- default of credit card clients.csv

**Statistics –**
Rows - 30000
Features - 25

**Columns:-** 
	'ID', 'LIMIT_BAL', 'SEX', 'EDUCATION', 'MARRIAGE', 'AGE', 'PAY_0', 'PAY_2', 	'PAY_3', 'PAY_4', 'PAY_5', 'PAY_6', 'BILL_AMT1', 'BILL_AMT2', 'BILL_AMT3', 	'BILL_AMT4', 'BILL_AMT5', 'BILL_AMT6', 'PAY_AMT1', 'PAY_AMT2', 	'PAY_AMT3', 'PAY_AMT4', 'PAY_AMT5', 'PAY_AMT6', 'default payment next month’.

# Problem Statement

* Our task is to build a model that predict the case of customers default payments in Taiwan.

* Conduct quantitative analysis on credit default risk by applying three interpretable machine learning models without utilizing credit score or credit history.

![image](https://user-images.githubusercontent.com/101592102/168750680-54b8da10-2380-4d06-b55d-46b3af66afb8.png)


# **Approach Overview**
![image](https://user-images.githubusercontent.com/101592102/168748551-3aad29ba-fdc9-4cbe-97ce-4f103097ef14.png)

# **Modelling Overview**

![image](https://user-images.githubusercontent.com/101592102/168748734-0c9ba026-df28-4d37-b666-679af6182faa.png)

# **Modelling Steps**

![image](https://user-images.githubusercontent.com/101592102/168748873-5a76587d-5a1e-40a8-899f-9f055645b1d9.png)


# **Model Prediction**

* Logistic Regression

* Decision Tree

* Random Forest Classifier

* XGBoost Classifier

# **Model Comparision**
![image](https://user-images.githubusercontent.com/101592102/168751016-51c2fc86-52c4-4f5d-8982-d1ca23bcb3b1.png)

![image](https://user-images.githubusercontent.com/101592102/168751088-80367cf5-b8aa-42f9-9141-540244f30253.png)


# **Conclusion**

Machine learning methods, in conjunction with the use of imbalanced methods, have been utilized in various domains. The objective of this paper is to train various supervised learning algorithms to predict the client’s behavior in paying off the credit card balance. In classification problems, an imbalanced dataset is also crucial to enhance the performance of the model, so different resampling techniques were also used to balance the dataset. We first investigated the datasets by using exploratory data analysis techniques, including data normalization. However, all the models implemented achieved comparable results in terms of accuracy.
* After performing the various model we the get the best accuracy form the Random forest and XGBoost classifier.

* Logestic Regression is the least accurate as compared to other models performed.

*  XGBoost has the best precision and the recall balance.

*  Higher recall can be achieved if low precision is acceptable.

*  We can deploy the model and can be served as an aid to human decision.

* Model can be improved with more computational resources and with more data.

