Customer Churn Analysis
Project Overview
This project analyzes customer churn for a telecom company using the Telco Customer Churn dataset. The goal is to explore factors influencing customer attrition and identify patterns that could help reduce churn rates. The analysis includes data cleaning, exploratory data analysis (EDA), and visualizations to uncover trends.

Dataset
The dataset contains 7,032 customer records with 21 features, including:

Demographic data (gender, SeniorCitizen, Partner, Dependents)

Service details (PhoneService, InternetService, Contract, PaymentMethod)

Financial metrics (MonthlyCharges, TotalCharges, tenure)

Target variable: Churn (whether the customer left the service).

Key Steps
Data Loading & Initial Inspection

Loaded the dataset and checked its structure, missing values, and data types.

Converted TotalCharges to numeric and handled missing values.

Exploratory Data Analysis (EDA)

Churn Distribution: Visualized the imbalance between churned (26.6%) and retained (73.4%) customers.

Summary Statistics: Analyzed tenure, MonthlyCharges, and TotalCharges.

Visualizations:

Histograms for tenure, monthly charges, and total charges.

Boxplot showing higher median MonthlyCharges for churned customers.

Key Findings
Churn Rate: 26.6% of customers discontinued services.

Financial Impact: Churned customers had higher median MonthlyCharges compared to retained ones.

Tenure: Longer-tenured customers were less likely to churn.

Potential Drivers:

High monthly costs.

Lack of long-term contracts (e.g., month-to-month plans).

Technologies Used
Python Libraries: pandas (data manipulation), matplotlib (visualization).

Tools: Jupyter Notebook.

Future Work
Build predictive models (e.g., logistic regression, random forest) to forecast churn.

Analyze correlations between services (e.g., OnlineSecurity, StreamingTV) and churn.

Recommend retention strategies (e.g., discounts for long-term contracts).


