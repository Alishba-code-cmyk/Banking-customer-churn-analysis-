# Banking-customer-churn-analysis-

## Phase 1 - project setup
### folders 
Banking-Customer-Churn-Analysis/
│
├── dataset/
│   └── Churn_Modelling.csv
│
├── notebooks/
│   └── Banking_Customer_Churn_Analysis.ipynb
│
├── reports/
│   └── Banking_Customer_Churn_Report.pdf
│
├── visualizations/
│
└── README.md

### download the dataset
https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction?utm_source=chatgpt.com
### install extensions
python 3.13.5 - Works well with Pandas, NumPy, Matplotlib and Seaborn.
jupyter- Working with .ipynb files.

## rule 
Jupyter Notebook execution order

Import libraries
Load dataset into df
Perform data analysis

If you restart the kernel, execute the cells again from the beginning. Variables do not survive a kernel restart.

## Phase 2 — Dataset Selection and Description


 ### Understand the target variable
Attribute             	Description
RowNumber	            Record number
CustomerId            	Unique customer identifier
Surname              	Customer surname
CreditScore	            Customer credit score
Geography	            Customer country
Gender	                Customer gender
Age	                    Customer age
Tenure              	Years with the bank
Balance	                Account balance
NumOfProducts	        Number of bank products
HasCrCard	            Credit card ownership (0/1)
IsActiveMember       	Active membership (0/1)
EstimatedSalary     	Estimated salary
Exited	                Churn status (0/1)

### Check the distribution
Interpretation:
- 0 represents customers who stayed.
- 1 represents customers who left.
- The percentage tells us the proportion of each group.

## Phase 3 — Data Preprocessing
investigate the following:
1. Missing values.
2. Duplicate records.
3. Data types and inconsistencies.
4. Outliers.
5. Final cleaned dataset.
