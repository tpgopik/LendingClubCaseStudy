# Lending Case Study
This project involves conducting Exploratory Data Analysis (EDA) for a consumer finance company specializing in lending. The objective is to identify patterns and insights using the historical applicants loan data to understand how consumer attributes influence the likelihood of loan defaults. The findings aim to inform decision making process on loan approvals while managing the risks effectively.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Develop a basic understanding of risk analytics in banking and financial services and understand how the provided data is used to minimise the risk of loan defaults and assist in decision making by uncovering patterns based on applicants profile. The dataset having historical information about applicants loan is been detailed (loan.csv) as part of the case study.

Technologies used:
- Python notebook within Anaconda suite
- Python 3 libraries
- Microsoft excel to analyse the loan data

Conclusions:
Univariate analysis Observations for categorical columns are as follows:
1) Grade distribution indicates Grade A loans are less likely to be defaulted compared to others
2) More defaults when the income source is 'Not Verified' and 'Verified'compared to 'Source verified'
3) Applicants with own houses are less likely to default than the onces on rent and mortgage
4) More number of loans are taken for 'debt cosolidation'
5) Most loans were given to applicants with employment of 10+ years
6) Default numbers for loans issued in the month of Feb is comparitively smaller in size

Bivariate analysis Observations are as follows:
1) Interest rate for 'Defaulters' are higher than 'Fully paid' customers
2) The quartiles of annual income for Defaulted applicants were lower then fully paid 
3) 'Revolving line utilization rate' was found to be higher for 'Charged off' or defaulted applicants.

Correlation between the numerical variables for charged off members:
The monthly payment owed by the borrower aka 'installment' is positively correlated with the loan amount.

Acknowledgement:
- I'm grateful to my buddy for her valuable contribution and hardwork and for being persistent and collaborative throughout the stint of this case study.Her expertise and support made a significant impact to the overall success.
- upgrad recorded videos were super useful to get to this point
- Online resources


## Contact
Created by [@tpgopik] - feel free to contact me!