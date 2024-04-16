# Bank-Defaulters-Case-Study

## Description: 
This case study aims to give us an idea of applying EDA in a real business scenario. In this case study, we will develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimize the risk of losing money while lending to customers.
 
## Business Understanding:
The loan-providing companies find it hard to give loans to people due to their insufficient or non-existent credit history. Because of that, some consumers use it to their advantage by becoming a defaulters.
Suppose we work for a consumer finance company that specializes in lending various types of loans to urban customers. We have to use EDA to analyze the patterns present in the data. This will ensure that the applicants capable of repaying the loan are not rejected.

## Findings:	
Our aim is to identify the patterns that indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of the loan, lending (to risky applicants) at a higher interest rate, etc.  
The driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  
Presenting the overall approach of the data analysis, cleaning the dataset, finding outliers, data imbalance, univariate, segmented univariate, bivariate analysis, etc.  
The top 10 correlations for the Client with payment difficulties and all other cases (Target variable).  

## Approach:	
Imported the NumPy, pandas, matplotlib, and seaborn python libraries.  
Imported the datasets (Application_Data & Previous_Application)   
Identification: We have identified how we will approach the data, finding the missing dataset and working on it accordingly to gain the required results.  
Outliers: Identified outliers and showed how they play if any role in our dataset.  
Imbalance: Understanding the ratio of imbalance in our data.   
Correlation Analysis: Find the correlation between the variables with respect to the target variables and find the top three correlations.  
Visualization: Visualized the data with the help of charts and graphs.  

## Insights: 
### 1.	Non-Default: 
The academic degree has fewer defaults.  
Students and Businessmen have no defaults.  
Clients with Trade Type 4 and 5 and Industry Type 8 have defaulted less than 3%.  
People above the age of 50 have a low probability of defaulting.  
Applicants with an Income of more than 700,000 are less likely to default.  
People with zero to two children tend to repay the loans.  
## 2.	Default: 
Men are at a relatively higher default rate.  
Clients who are either on Maternity leave OR Unemployed default a lot.  
Not approving the loan of young people who are in the age group of 20-40 as they have a higher probability of defaulting.  
When the credit amount goes beyond 3M, there is an increase in defaulters.  
People who have less than 5 years of employment have a high default rate.  


