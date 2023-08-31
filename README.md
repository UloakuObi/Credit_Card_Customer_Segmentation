# Credit_Card_Customer_Segmentation

**Project Overview:**

In this project, we’ll play the role of a data scientist working for a credit card company. We’ve been given a dataset containing information about the company’s clients and asked to help segment them into different groups in order to apply different business strategies for each type of customer.

The company expects to receive a group for each client and also an explanation of the characteristics of each group and the main points that make them different.

In a planning meeting with the Data Science coordinator, it was decided that we should use the K-means algorithm to segment the data.

In order to use the algorithm properly and achieve all the goals that the company has set for us, we'll go through the following steps:

* Analyse the dataset;
* Prepare the data for modeling;
* Find an appropriate number of clusters;
* Segment the data;
* Interpret and explain the results.

### Data Dictionary:

* `customer_id`: unique identifier for each customer.
* `age`: customer age in years.
* `gender`: customer gender (M or F).
* `dependent_count`: number of dependents of each customer.
* `education_level`: level of education ("High School", "Graduate", etc.).
* `marital_status`: marital status ("Single", "Married", etc.).
* `estimated_income`: the estimated income for the customer projected by the data science team.
* `months_on_book`: time as a customer in months.
* `total_relationship_count`: number of times the customer contacted the company.
* `months_inactive_12_mon`: number of months the customer did not use the credit card in the last 12 months.
* `credit_limit`: customer's credit limit.
* `total_trans_amount`: the overall amount of money spent on the card by the customer.
* `total_trans_count`: the overall number of times the customer used the card.
* `avg_utilization_ratio`: daily average utilization ratio. 0

## Conclusion
By taking note of the most important characteristics of each cluster, we can draw some valuable insights on how to better tailor both business and marketing strategies to better meet the needs of each type of customer.

Each customer in the dataset has been assigned to a cluster, here are the general features of each cluster:

* `Cluster 1`: This cluster represents individuals with moderate incomes and credit limits who use their credit cards moderately, regardless of gender and marital status, suggesting a balanced approach to credit card usage.

* `Cluster 2`: This group consists of financially cautious, predominantly single women with limited income and credit access, indicating a focus on controlled credit usage while managing within their financial means.

* `Cluster 3`: This cluster signifies affluent, responsible married men who use credit sparingly for high-value transactions, showcasing strong financial stability and a preference for controlled credit card usage.

* `Cluster 4`: This cluster consists of mostly married or divorced women with lower incomes and credit limits, exhibiting conservative credit behavior and lower transaction volumes, possibly driven by their financial circumstances.

* `Cluster 5`: Both married and single men in this cluster enjoy higher credit limits, engage in substantial transactions, and maintain a reasonable credit utilization ratio, highlighting a balanced and proactive credit usage pattern.