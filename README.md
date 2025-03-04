![](images/CustomerChrun.png)

## Overview

Customer churn, also known as customer attrition, is when customer chooses to stop using the products or services of the company and stops the relationship. It is a critical metric for any business. Churn can be voluntary (customers leaving due to dissatisfaction or better alternatives etc) or involuntary (due to reasons like payment failures, fraud etc).  
The primary objective of this analysis is to identify the factors that contribute to customer churn and make a predictive model that can forecast if the customers are likely to leave 

## Dataset

The dataset used is a Telecom churn dataset (customer_churn_dataset-training-master.csv and customer_churn_dataset-testing-master.csv) from Kaggle.

File Path:  

https://github.com/CoderNBR/Customer-Churn/blob/main/data/customer_churn_dataset-training-master.csv  
https://github.com/CoderNBR/Customer-Churn/blob/main/data/customer_churn_dataset-testing-master.csv

The datasets together contains about 500K rows and 12 feature columns including target feature:

Input Variables:

    - CustomerID: Unique identifier for a customer
    - Age: Age of the customer
    - Gender: Gender of the customer
    - Tenure: Duration in months for which a customer has been using the company's products/services
    - Usage Frequency: Number of times the customer has used the company’s services in the last month
    - Support Calls: Number of calls the customer has made to the customer support in the last month
    - Payment Delay: Number of days the customer has delayed their payment in the last month
    - Subscription Type: Type of subscription choosen by the customer
    - Contract Length: Contract duration that the customer has signed with the company
    - Total Spend: Total amount the customer has spent on the company's products or services
    - Last Interaction: Number of days since the customer had the last interaction with the company

Output Variable (Target):

    - Churn: Binary label indicating whether a customer has churned (1) or not (0) 

## Approach

1. Importing Data
2. Data cleaning
    - Clean the column names if required
    - Duplicate Check
    - Missing Value Check
    - Drop unwanted column(s)
3. Exploratory Data Analysis (EDA)
4. Data Pre-processing
5. Modelling


## Visualizations

1. [Histograms](https://github.com/CoderNBR/Customer-Churn/blob/main/images/Histograms.png)
2. [CorrelationHeatmap](https://github.com/CoderNBR/Customer-Churn/blob/main/images/CorrelationHeatmap.png)
3. [Distribution Of Churn](https://github.com/CoderNBR/Customer-Churn/blob/main/images/DistributionOfChurn.png)
4. [Distribution Of ContractLength](https://github.com/CoderNBR/Customer-Churn/blob/main/images/DistributionOfContractLength.png)
5. [Distribution Of Gender](https://github.com/CoderNBR/Customer-Churn/blob/main/images/DistributionOfGender.png)
6. [DistributionOfSubscriptionType](https://github.com/CoderNBR/Customer-Churn/blob/main/images/DistributionOfSubscriptionType.png)
7. [Gender VS Churn](https://github.com/CoderNBR/Customer-Churn/blob/main/images/GenderVSChurn.png)
8. [PaymentDelay VS Churn](https://github.com/CoderNBR/Customer-Churn/blob/main/images/PaymentDelayVSChurn.png)
9. [Subscription Type VS Churn](https://github.com/CoderNBR/Customer-Churn/blob/main/images/SubscriptionTypeVSChurn.png)
10. [SupportCalls VS Chrun](https://github.com/CoderNBR/Customer-Churn/blob/main/images/SupportCallsVSChrun.png)
11. [Boxplot of Total Spend Amount](https://github.com/CoderNBR/Customer-Churn/blob/main/images/TotalSpendAmountBoxplot.png)
12. [KDE_X_train](https://github.com/CoderNBR/Customer-Churn/blob/main/images/KDE_X_train.png)
13. [KDE_X_train_scaled](https://github.com/CoderNBR/Customer-Churn/blob/main/images/KDE_X_train_scaled.png)

  
## Next Steps

1. Train different models to compare
2. Use cross validation techniques and hydepertuning params to improve on those models


## Repository Link (GitHub)

1. [GitHub Link for "Customer Churn Analysis"](https://github.com/CoderNBR/Customer-Churn)
2. [Jupyter Notebook](https://github.com/CoderNBR/Customer-Churn/blob/main/CustomerChurn_EDA.ipynb)
