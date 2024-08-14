# Customer-Churn-Analysis
Overview:

Customer churn analysis is a crucial process for businesses aiming to understand why customers leave and to identify strategies to retain them. It involves analyzing historical data to uncover patterns and factors that contribute to customer attrition. By understanding these factors, companies can implement targeted interventions to reduce churn rates and enhance customer loyalty.

Problem Statement:

In the context of customer churn analysis, the primary problem is to determine which customers are likely to churn (i.e., discontinue using a product or service) and understand the underlying reasons behind their decision.

The Questions to be asked based on this analysis are:
•  What is the overall churn rate for the company, and how has it changed over time?

•  Which customer segments (e.g., by age, gender, location) have the highest churn rates?

•  What are the common characteristics or behaviors of customers who churn?

•  What are the main reasons cited by customers who have churned, based on feedback or survey data?

•  How does customer engagement (e.g., frequency of usage, interaction with customer support) correlate with churn rates?

•  Are there any specific features or services associated with higher churn rates?

•  What impact do promotional offers or discounts have on reducing churn?

•  How do customer satisfaction scores or Net Promoter Scores (NPS) relate to churn rates?

•  What predictive models can be developed to accurately forecast customer churn?

•  What are the financial implications of customer churn, and how can the company measure the cost of acquiring new customers versus retaining existing ones?

Project Objective:

The objective of this analysis is to discover various factors contributing to increased customer churn rate at the bank, and provide the business users with these insights which they can use to make informed decisions and strategize on how to improve customer retention and reduce churn rate.

Tools: I used Power BI, Power Query and Ms Excel for this analysis.

Data Dictionary

customer_id: This is the customers’ unique id which identifies them bankwide.
credit_score: this is the rating of the customers’ credit worthiness, generated based on the information on their credit report.
country: This is the country the customer hails from.
gender: This is the sex of the customer, grouped into male and female.
age: This refers to the customer’s age.
tenure: The number of years of relationship this customer has maintained with the bank.
balance: The deductible balance on their bank account as at time this data was generated.
products_number: This shows the bank account type the customer has.
credit_card: This column shows if a customer has a credit card or not, represented as either 1 or 0 respectively.
active_member: These numerical values show whether an account is active or not, represented as either 1 or 0 respectively.
estimated_ salary: This is the average annual salary received into the account.
churn: This field shows if the customer is still with the bank or not, represented by either 0 or 1 respectively.

Analytical Steps

Data Preparation
Data Categorization and Grouping
Formatting
Data Transformation
Data Modeling
Visualisation — Report
Insights
Recommendation
Conclusion

Insights

Churn rate for male customers is 65% but the overall male churn rate is at 25%.
In terms of those with credit card facility, the churn rate is highest amongst lowest credit score group of >400
Surprisingly, the customers whose account balance are <=200k are the most churned in terms of account balance.
Overall, Churn rate is very high at 56.2% for middle aged customers between 51–60 years of age.
For the products, churn rate is high @ 27.7% amongst customers in the Prod 1 group. The age account and credit score factors are same here. Similar situation for prod 2 =, however in prod 2, the churn rate is at all time 100% for customers between the 1k-1ok account balance.
