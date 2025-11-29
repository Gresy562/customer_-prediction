Customer Churn Prediction (Machine Learning Project)
Project Overview:-
---Customer churn prediction helps businesses identify customers who are likely to leave their services.
---In this project, we analyze telecom customer data, clean and preprocess it, build predictive ML models, and evaluate their performance.
---This project is ideal for Data Science beginners and demonstrates end-to-end ML workflow skills.

Dataset:-
Dataset Used: Telco Customer Churn Dataset
..Rows: 7043
..Columns: 21
..Target Variable: Churn (Yes/No)
..Contains data about customer demographics, services, billing, contract type, and payment details.
(If you uploaded the dataset in your repo, add this line)
**customer_churn_full_dataset.csv is included in this repository.

Problem Statement:-
---Predict whether a customer will churn (leave the service) based on their service usage and account information.

Technologies Used:-
---Python
---Jupyter Notebook
---Panas, NumPy
---Matplotlib, Seaborn
---Scikit-Learn
---Logistic Regression, Random Forest, XGBoost (optional)

Data Preprocessing:-
✔ Handling missing values
✔ Converting TotalCharges to numeric
✔ Outlier detection
✔ Encoding categorical variables
✔ Scaling numerical features
✔ Train–Test split

Exploratory Data Analysis
Key insights discovered:
---Customers using month-to-month contracts are more likely to churn
---High monthly charges increase churn probability
Longer tenure means lower churn
Electronic check payment method users churn more
Visualizations Included:
... Distribution plots
... Correlation heatmap
... Churn vs Contract type
... Churn vs Monthly charges

Machine Learning Models Used:-
1️) Logistic Regression
...Baseline model
...Easy to interpret
2️) Random Forest Classifier
...Best performance
...Handles categorical and numerical data well
...Good feature importance insights
3️) (Optional) XGBoost
...High accuracy
...Works well for imbalanced datasets

Feature Importance:-
---Top factors influencing churn:
---Contract Type
---Tenure
---Monthly Charges
---Internet Service Type
---Payment Method

conclusion:-
This project provides a complete workflow for predicting customer churn using machine learning techniques. 
The final model effectively identifies customers at a higher risk of churn and can be used as a foundatio for building data-driven retension strategies.


