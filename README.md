# Telco Customer Churn Analysis & Predictions

## Project Description

The main goal of this project is to predict the Customers behavior to retain them. Cleaning and understanding the data are the firts steps to obtain better conclusions. Finally, I will make several machine learning models to see with wich one I get better accuracy detecting churns. 

## Motivation

As a Telecomunications Engineer I have been always interested in phone compnies and their enviroment. Now, I am starting analysing data so the best way to choose one of my first projects is combining data analysis with my old passion and here is the result. 

## Dataset 

You can found the dataset in FILES folder as "Telco-Customer-Churn.csv". You can also download it in the following link: https://www.kaggle.com/blastchar/telco-customer-churn 

Each row represents a customer and each column contains customer’s attributes. The dataset contains 7043 rows (1 for each customer) and 21 columns (different features about the customers). The target is the column called 'Churn' which tell us what customers left within the last month.

## Files
- The main file is TelcoProject.ipynb
- The file TelcoMachineLearning.ipynb is a reduced version which contains only the Machine Learning model results.
- The final presentation can be found here: https://public.tableau.com/app/profile/v.ctor3960/viz/TelcoProject_16445774068370/Story1?publish=yes

## How to understand and work with the project

Opening the notebooks you will observe that the project is auto-guided and there are explanations about almost all the steps I'm doing so it will be easy to understand what I'm doing in each moment.

## Presentation explanation

> 1. Project intro.

> 2. The number of customers who decided to leave the company is less than 30%.

> 3. Services intro.

> 4. Can see that those customers with fibre optics, who are also the ones who pay the most, are much more likely to leave the company
Can see that customers who pay by electronic check must be having some problems as they are more than twice as likely to leave the company. 
Can observe that those customers with shorter contracts are more likely to leave.

> 5. Can observe that seems these "extra services2 work well because those who have them have a much higher probability of staying with the company.

> 6. Gender and Streaming TV almost have no impact.

> 7. Prices intro.

> 8. Customers who decide to leave the company are paying a higher average monthly bill.

> 9. For the most common services we see that the prices vary reasonably but, in extra services we can see some peculiarities:
> - The Online Security contract almost does not change the price of the bill.
> - The price increase for having both, Tech Support and Online Security, is not remarkable.

> 10. Senior citizens intro.

> 11. On the left, can see that the number of senior customers is much lower, as expected, but churn is much more common in this age group
> On the right, can observe that the senior customers bill is well above average

> 12. ML intro.

> 13. ML conclusions: LR with Oversampling is able to predict almost 80% of customers who want to leave the company.








