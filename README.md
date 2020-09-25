# Nicholas Krajewski's Data Science Portfolio
My data science portfolio of personal and exploratory projects. 

# [Project 1: Fantasy Baseball Prediction Model](https://github.com/nkrajew/baseball_proj)
- Created a machine learning model to predict MLB players’ offensive fantasy value for the next season given their past statistics to help in future fantasy baseball drafts.
- Compared output of model to historical ADP rankings to see if the model gave me an edge over ADP.
- Downloaded 9 years of historical data (2010-2018) from FanGraphs.
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
- Recommended mitigation strategies for each factor.

![](/images/inc_attrit_resize.PNG)
![](/images/env_sat_resize.PNG)
![](/images/attrit_by_tenure_resize.PNG)

# [Project 3: Loan Prediction](https://github.com/nkrajew/loan_proj)
- Created a machine learning model (accuracy = 75%) to predict if a loan applicant will have their application approved.
- Used loan data provided from Kaggle.
- Engineered features from the data to identify families with single earners.
- Performed value imputation for entries with missing data.
- Optimized Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors models using GridSearchCV.

![](/images/dist_plot_pre_resize.PNG)
![](/images/dist_plot_post_resize.PNG)
![](/images/results.PNG)

# [Project 4: Music Lyrics Wordcloud](https://github.com/nkrajew/lyrics_wordcloud)
- Created a word cloud visualization based on a musical artist's lyrics
- Scraped data from the Genius Lyrics website using BeautifulSoup
- Processed and cleaned the data using RegEx

![](/images/NF_wordcloud.png)

# ADDITIONAL PROJECTS/WORK
# [Data Science Salary Estimator](https://github.com/nkrajew/ds_salary_proj)
*Disclaimer: This project is **strongly** based off of Ken Jee's tutorial. Much of the code used is his with minor tweaks by me to better incorporate the data I pulled.*

- Created a data science salary estimation tool (MAE ~$25K) which could help data scientists negotiate their income when they are offered a job.
- Scraped 1000 job descriptions from glassdoor using Python and Selenium.
- Engineered features from the job description text.
- Optimized Linear, Lasso, and Random Forest regressors using GridSearchCV to find the best model to productionize.
- Productionized the model by building a client facing API using Flask.

![](/images/pivot.PNG)
![](/images/corr_2.PNG)
![](/images/state_jobs_resize.PNG)
