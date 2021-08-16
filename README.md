# Capstone5-Bank-Marketing-Campaign
Purpose Of Project

The purpose of this project is to identify the effectiveness of the marketing campaign launched by the Portuguese Bank for getting their customers to subscribe for term deposits.  As an analyst of the bank, analysis of the marketing campaign data is done and several ML models are created to predict the probability of whether a customer will subscribe for term deposits. In addition, insights and recommendations will be provided to the sales team to target on the specific group of customers to increase the subscription rate.

<b>Data Source</b>
For this project, the data source is from Kaggle. 
Link : https://www.kaggle.com/edith2021/bank-marketing-campaign
![image](https://user-images.githubusercontent.com/34051347/129523506-127dca03-6ec2-49b4-96f1-8ec59b8c2c8c.png)

<b>Data Preparation for Maching Learning Models</b>
![image](https://user-images.githubusercontent.com/34051347/129523688-a9a0ed73-526a-4ec4-9503-901603a26537.png)
As from the chart above, we can see a huge imbalanced of data between the number of customers who has not subscribed for the term deposits(majority) vs those who have subscribed(minority). Hence, SMOTE is being used here to create the synthetic data from the minority class.

<b>Machine Learning Models and Results</b>
![image](https://user-images.githubusercontent.com/34051347/129524361-8b70c1dc-c096-44cc-a912-1d33337b8cb8.png)

<b>Power BI Dashboard</b>

#Dashboard Overview

![image](https://user-images.githubusercontent.com/34051347/129524847-a83a1d0c-f0e6-422d-ad13-d68d789897bd.png)

From here we can see the overview of the dashboard, with a total of 30.91k customers, but only having 4513 of them subscribing to the term deposit.

# Contact Medium

![image](https://user-images.githubusercontent.com/34051347/129524994-931c7c5f-1431-4250-99ac-b7c06b151332.png)


Majority of the contact medium are cellular(> 90%)

# Profession
![image](https://user-images.githubusercontent.com/34051347/129525183-98f4e575-dfd7-45a3-8c0c-f63ea1952503.png)

From here we can see the breakdown of the various professions, management, technician and blue-collar holding the top 3 spots. Further analysis will be done later on.

# Campaign Monthly Performance
![image](https://user-images.githubusercontent.com/34051347/129525390-ccf3ce97-bfc6-4908-b348-840d7065eda0.png)

From here we can see the top 3 months that has conducted the most marketing(by customer count) are from the month of July, August and May.

# Customer by Age Group
![image](https://user-images.githubusercontent.com/34051347/129525513-0b63a7d8-c644-4efd-989b-3f41fdba6899.png)

When comparing in terms of age group, we can see the younger crowd(25 and under) and those that are above 60, has a larger % of them subscribing to the term deposits.
Whereas for the inbetweens(25-60), are more likely to not have any terms deposits subscription probably due to more commitments in life(Starting family/businesses etc)

# Contact Overview

![image](https://user-images.githubusercontent.com/34051347/129525739-08a9e186-c265-4870-94aa-fd439410471f.png)

# Average Duration Of Call

![image](https://user-images.githubusercontent.com/34051347/129526435-c1012f55-3b3a-49a4-a05e-121a233d27be.png)

Call duration are likely to be longer as it make sense where customers who are interested in term deposits are more likely to be getting more information during the call, hence the length of call is significantly higher than the average of those that did not subscribe term deposits.

![image](https://user-images.githubusercontent.com/34051347/129526901-6e1637fe-d2f6-4fa3-be39-d538855de77e.png)

# Total Contact Duration(Minutes) For Campaign

![image](https://user-images.githubusercontent.com/34051347/129526936-cabba337-1dec-47f3-93ca-994cf7c86bc1.png)

As the top 3 months for marketing campaigns are July, August and May, it is evident that the number of minutes done during the campaign are generally the highest in this three months.

# Client Information Overview

![image](https://user-images.githubusercontent.com/34051347/129527298-054e1fa0-8a78-4e2d-8c63-883954eb14fc.png)

Here is an overview of all customer's information, which contains the educational level, loans that the customers have, marital status and profession.

# Analysis Overview

![image](https://user-images.githubusercontent.com/34051347/129527476-30ca15a5-ea78-4ebd-8b0b-34fc6ed31b4c.png)


From the marketing campaign data, we can see that the bank is only getting a subscription rate of 14.6%, only having 4513 subscribers among the 31k customers that they have contacted. This is definitely way under what they are likely to expect.

# Profession Analysis

![image](https://user-images.githubusercontent.com/34051347/129527649-58e4964e-3826-46f2-a2b4-8cfdf59845a1.png)

In overall, we can see that 76% of the subscribers come from the top 5 professions, which are : Management, Technician, Admin, Blue-collar and Retired. Hence, it is recommended that this group of professions should be targetted to achieve higher subscription rate.

# Loans Analysis

![image](https://user-images.githubusercontent.com/34051347/129527810-95964cf2-7ffe-487b-9247-bece90db0427.png)

Judging from the customers and their loans, be it looking at each category or as a whole, we can see that the majority of them actually comes from the 'No Loan' group, which suggests that these group of people are likely to have more available cash for term deposits.

# Time Analysis

![image](https://user-images.githubusercontent.com/34051347/129528010-f52b5849-9346-4329-ba78-00fd727a2cda.png)

As discussed earlier,  we can conclude that the length of the call duration will impact the subscription rate of the customers. The longer the call duration is likely to make customers signing up for term deposits, suggesting that the customer is interested in the product and wants to know more. Hence, it is recommended that the salesperson have to try to make it more interactive during the call, to increase the subscription rate.

# Conclusion and Recommendation

![image](https://user-images.githubusercontent.com/34051347/129528310-2b6742f9-0844-4e65-8f19-8c1e70e4d710.png)

Based on the analysis done previously, we can recommend that these particular group of customers should be targetted for the upcoming marketing campaign, which is likely to have a higher subscription rate than current(14.6%). 

The group will be from:
Profession : Blue-Collar, Management, Retired, Admin and Technician.
They should not have any loans.
Try to make more interactive calls, a longer call duration is likely to have a positive outcome.










 
