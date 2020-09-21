# Nicholas_Portfolio
My data science portfolio

# [Project 1: Fantasy Baseball Prediction Model: Project Overview](https://github.com/nkrajew/baseball_proj)
- Created a machine learning model to predict MLB players’ offensive fantasy value for the next season given their past statistics to help in future fantasy baseball drafts.
- Compared output of model to historical ADP rankings to see if the model gave me an edge over ADP.
- Downloaded 9 years of historical data (2010-2018) from FanGraphs (link in Data Sources section below).
- Manipulated the raw data to create a "Fantasy Value" which was used as the target value.
- Optimized Linear, Elastic Net, Random Forest, XGBoost, LightGBM, and SVM models using GridSearchCV (LightGBM used BayesianOptimization) to reach the best model.

![](https://github.com/nkrajew/Nicholas_Portfolio/blob/master/images/corr_matrix_image.png )
![](https://github.com/nkrajew/Nicholas_Portfolio/blob/master/images/pair_plot_resized.png)
![](https://github.com/nkrajew/Nicholas_Portfolio/blob/master/images/target_distribution.png)

# [Project 2: HR Analytics - Employee Attrition: Project Overview](https://github.com/nkrajew/hr_attrition_proj)
*Disclaimer: Data is fictitious*
- Created an Extreme Gradient Boosting model using SMOTE to predict if an employee would leave the company (Recall: 0.77, Accuracy: 0.88).
- Compared output to XGB model without SMOTE (Recall: 0.31, Accuracy: 0.86).
- Identified Job Role - Healthcare Rep, Job Level 1, Job Involvement 4, and Business Travel - Non-Travel as most important factors.
- Recommended mitigation strategies for each factor (detailed below).
![](https://github.com/nkrajew/Nicholas_Portfolio/blob/master/images/inc_attrit.PNG)
![](https://github.com/nkrajew/Nicholas_Portfolio/blob/master/images/env_sat.PNG)
![](https://github.com/nkrajew/Nicholas_Portfolio/blob/master/images/attrit_by_tenure.PNG)
