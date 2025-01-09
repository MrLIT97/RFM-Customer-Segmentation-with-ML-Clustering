# RFM-Customer-Segmentation-with-ML-Clustering

## Introduction: 
SPROCKET CENTRAL PTY LTD, a company that deals in the sales of bicycle requires that their customer records be analysed for adequate customers segmentation. The aim is to better understand the strata of their customers based on profitability so as to guide subsequent marketing strategies. For this purpose, an RFM (Recency, Frequency, and Monetary) analysis was done using K-means clustering. Corresponding RFM columns were calculated from the dataset. After segmentation, further analysis was done and visualised in Power BI for reportability.

## Dataset Description:
The dataset was provided by KPMG for a virtual internship programme. It is a flat file gotten from the combination of separate files named: CustomerAddress, CustomerDemographics, and Transactions. It is a mixture of continuous and discrete variables with 13,861 observations and 29 features. Major features used for this analysis include: 

customer_id - unique identity for each customer

transaction_id - unique identity for each transaction

transaction_date - date for each transation

list_price - product price

standard_cost - production cost

Other features involve:

gender

DOB - Date of Birth

job_title

job_industry_category, etc.

## Expertise Demonstrated:

1. Data cleaning
2. Exploratory Data Analysis
3. Data manipulation
4. Unsupervised Machine Learning modeling (K-means Clustering)
5. Data Visualization

## Tool used:
* Excel
* Python
* Power BI

## Machine Learning methods:
* Mode selected = K-means clustering (since the clustering was based on recency, frequency and monetary which are all numeric)
* Feature Scaling using Standard Scaler
* Identifying best number of clusters using the **elbow method** 

## Result:
Based on clustering, a customer segment column named **Spending Class** was introduced which groups customers based on how profitable they are to the company.

## Dashboad:
![rfm1](https://github.com/user-attachments/assets/2166c38d-91b5-40de-b7a6-0104fbd52f44)
![rfm2](https://github.com/user-attachments/assets/e7267d4c-0b0f-4cec-b37b-838152ace8d0)


