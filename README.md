<h1>Lasso and Ridge Regression</h1>
<h2>Domain: Statistics for Machine Learning</h2>
This is not a project kind of thing. This Jupyter repository is purely for comparision analysis between two regression 
techniques which are used to solve the problem of Overfitting. <br>
Channel I followed: <a href="https://www.youtube.com/c/codebasics">Codebasics</a><br>
Dataset I used: <a href="https://www.youtube.com/c/codebasics](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot">Melbourne Housing Snapshot </a><br><br>
<b>Problem Statement: </b> To perform a comparative analysis between three techinques in regression. And decide the most efficient algorithm from inear Regression, Lasso Regression and Ridge Regression that solves the problem of Overfitting.
<br><br>

<b>Problem of Overfitting: </b> Overfitting happens when our model is only suitable to perform well on the seen/ trained data and it fails to perform well on unseen data. Overfitting occurs when our machine learning model tries to cover all the data points or more than the required data points present in the given dataset. Because of this, the model starts caching noise and inaccurate values present in the dataset, and all these factors reduce the efficiency and accuracy of the model. The overfitted model has low bias and high variance.

<b>Regularization- Solution to Overfitting: </b><br>
Regularization is implemented by adding a “penalty” term to the best fit derived from the trained data, to achieve a lesser variance with the tested data and also restricts the influence of predictor variables over the output variable by compressing their coefficients. In regularization, what we do is normally we keep the same number of features but reduce the magnitude of the coefficients. We can reduce the magnitude of the coefficients by using different types of regression techniques which uses regularization to overcome this problem.There are three types of regularization as follow:
<br>
1. L1 Regularization<br>

![image](https://user-images.githubusercontent.com/88442486/184533851-34271070-e3c4-45f2-91b5-bc6ae54fb119.png)

2. L2 Regularization<br>

![image](https://user-images.githubusercontent.com/88442486/184533857-1b798e3a-5741-42c0-83c8-263b4bc35e5e.png)

3. Dropout Regularization<br><br>


There are two main regularization techniques, namely Ridge Regression and Lasso Regression. They both differ in the way they assign a penalty to the coefficients.Ridge and Lasso regression are some of the simple techniques to reduce model complexity and prevent over-fitting which may result from simple linear regression.<br><br>

<b>Further Studies:</b> https://www.analyticsvidhya.com/blog/2017/06/a-comprehensive-guide-for-linear-ridge-and-lasso-regression/
