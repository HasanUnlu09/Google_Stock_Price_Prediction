# Google Stock Price Prediction

## Project Description
In this project, it is aimed that predicting stock price for a company and Google is selected to be the subject company of this project. In order to obtain data, Yahoo Finance API is used and the obtained data is between *August 19, 2004* and *December 1, 2023*. If you would like to see content of the dataset, you can check out the dataset in the **Google_Stock_Price_Dataset.csv** file. In order to accomplish prediction operation, following **Regression ML Algorithms** are used, **Linear Regression**, **K-Nearest Neighbors Regression**, **Random Forest Regression**, **Decision Tree Regression**, **Ridge Regression** and **Gaussian Regression**. These ML Algorithms are evaluated by using **R_Squared** and **Mean Squared Error** metrics. As a result of these algorithms, best performed models are *Linear Regression* and *Gaussian Regression* algorithms although all other algorithms performed quite well. According to evaluation results, Linearity Assumptions are checked in order to interpret because one of the best performing models is Linear Regression. It should be mentioned that, Data Science Project LifeCycle is followed on this project to effectively simulate business level project handling as it can be seen from the following image. Therefore, project is formed in to 7 steps with the proceduralized contents and the step/file names are as follow; **1. Business_Understanding**, **2. Data_Mining**, **3. Data_Cleaning**, **4. Data_Exploration_(EDA)**, **5. Feature_Engineering**, **6.  Predictive_Modelling_&_Evaluation** and **7. Data_Visualization**.  

![Data_Science_LifeCycle](https://github.com/HasanUnlu09/Google_Stock_Price_Prediction/assets/133260754/5fff2ff5-8ec6-47f4-a2f3-4224eb56fe43)

## Install/Run
Each Data Science LifeCycle steps in Jupyter Notebook files can be runned one by one on your computer to see the results. If you want more generalized and compact file you can download and run *Google_Stock_Price_Prediction.ipynb* Jupyter Notebook. Also, it must be mentioned that **Google_Stock_Price_Dataset.csv** file will be changed by the date you run the **2. Data_Mining.ipynb** file. Thus, outputs of the models and evaluations will be different from the ones in the project files. As same, if the *Google_Stock_Price_Prediction.ipynb* file run, then dataset that is stored in the *stock_data* data frame will be changed. In order to avoid this situation, you can read *Google_Stock_Price_Dataset.csv* file instead of using Yahoo Finance API for the dataset obtaining.

## Project Outcomes
Below image shows that Google stock price distribution over time as both Line Plot and Scatter Plot;
![Google_Stock_Price_Distribution_Over_Time](https://github.com/HasanUnlu09/Google_Stock_Price_Prediction/assets/133260754/0b629080-7386-42d2-b463-8a0d012334de)

Below image shows that evaluation results of each ML models;
![Evaluation_Results_For_Each_ML_Models](https://github.com/HasanUnlu09/Google_Stock_Price_Prediction/assets/133260754/792abee5-175d-4c84-a62e-b6a66e5ca1f8)


Below image shows that Actual stock prices and Prdicted stock prices over time on the  same graph. Thus, it can be seen that models are performed almost perfectly which might cause from the overfiftting issue.
![Predicted_Actual_Sock_Price_Distribution_Over_Time_In_The_Same_Plot](https://github.com/HasanUnlu09/Google_Stock_Price_Prediction/assets/133260754/e1316157-761a-4d6f-ba62-a82c9770db1f)


!!! If you would like to reach me out about this project you can use following e-mail address;
**hasan.09.unlu@gmail.com**
