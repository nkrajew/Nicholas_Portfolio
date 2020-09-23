# Nicholas Krajewski's Data Science Portfolio
My data science portfolio of personal and exploratory projects. 

# [Project 1: Fantasy Baseball Prediction Model](https://github.com/nkrajew/baseball_proj)
- Created a machine learning model to predict MLB players’ offensive fantasy value for the next season given their past statistics to help in future fantasy baseball drafts.
- Compared output of model to historical ADP rankings to see if the model gave me an edge over ADP.
- Downloaded 9 years of historical data (2010-2018) from FanGraphs (link in Data Sources section below).
- Manipulated the raw data to create a "Fantasy Value" which was used as the target value.
- Optimized Linear, Elastic Net, Random Forest, XGBoost, LightGBM, and SVM models using GridSearchCV (LightGBM used BayesianOptimization) to reach the best model.

![](/images/corr_matrix_image_resize.png)
![](/images/pair_plot_resize.png)
![](/images/target_distribution.png)

# [Project 2: HR Analytics - Employee Attrition](https://github.com/nkrajew/hr_attrition_proj)
*Disclaimer: Data is fictitious*
- Created an Extreme Gradient Boosting model using SMOTE to predict if an employee would leave the company (Recall: 0.77, Accuracy: 0.88).
- Compared output to XGB model without SMOTE (Recall: 0.31, Accuracy: 0.86).
- Identified Job Role - Healthcare Rep, Job Level 1, Job Involvement 4, and Business Travel - Non-Travel as most important factors.
- Recommended mitigation strategies for each factor (detailed below).

![](/images/inc_attrit_resize.PNG)
![](/images/env_sat_resize.PNG)
![](/images/attrit_by_tenure_resize.PNG)

# [Project 3: Loan Prediction](https://github.com/nkrajew/loan_proj)
- Created a machine learning model (accuracy = 75%) to predict if a loan applicant will have their application approved.
- Used loan data provided from Kaggle (link below).
- Engineered features from the data to identify families with single earners.
- Performed value imputation for entries with missing data.
- Optimized Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors models using GridSearchCV.

![](/images/dist_plot_pre_resize.PNG)
![](/images/dist_plot_post_resize.PNG)
![](/images/results.PNG)
