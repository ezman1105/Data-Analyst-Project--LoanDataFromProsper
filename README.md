# Project -- Loan Data in Prosper
## by Chih-Chuan Ma


## Dataset

> The dataset records the information of personal loan from Prosper Funding LLC, which mainly runs the business of lending money, creidt card, home equity and personal investment. The oringal dataset contains up to 113,937 data and 81 variables, including range of income, the purpose of loan, region, status of employment, result of the loan application, and even the frequencies of loan inquiries in a certain time span..etc.

> In this project, preliminary data wrangling, such as missing data and duplicates removal, will be performed. Also, the value of a certain features, such as  occupation, listing of categories and duration of employment level, are transformed for better understanding. A few nenessary variables for further analysis are reserved as well. The main interest of the analysis is to explore the relationships among cost of borrowering (the APR) and various features. As requested, the data will be investegated followed by visualization of univariate, bivariate, and multi-variate plots.


## Summary of Findings

> The time span of the data is 8 years from 2007 to 2014, and up to 92% of applicants have full-time job and employed. The range of stated monthly salary and revolving credit balance of most borrowers is from 1.2K to 12K and 1K to 100K accordingly; the mojarity of loan purpose is to consolidate the debt. In addition, there are 40% people with more than 90 months working experience. 60% of annual salary ranges from 25,000 to 74,999 while the percentage for those in the group of high annual income (more than 75,000) is around 32%. However, at least one third of "real" occupation is still not clear since the it is categorised as "Other" and "Professional"

> A strong negative correlation among upper and lower range of credit score and annual percentage rate can be observed, which is reasonable for borrowers who have better credits enjoy better conditon of loan. Other features with negative correlation with annul percentage rate (APR) include available bankcard credit, the orginal amount of loan, the percentage of trades never delingquent, and monthly loan payment. On the other hand, the higher utilization of bank card causes higher cost of borrowing. Furthermore,People whose employment status categorized as "Other" have highest cost of borrowing while similar level of APR can ben seen for those who have full-time, part-time job, not-employed and self-employed. From the perspective of income range, generally speaking, the higher annual income leads to the lower cost of borrowing. Interestingly, borrowers who are out of job enjoy the same level of APR as those with the highest annual income. Among the top 8 purposes of loan, it's most expenseive if the money is borrowed for house expenses; engnineers and business executives enjoy th least average APR and the similar APR level is seen for the rest occupations.

> It's beneficial to acquire lower annual percentage rate if borrowers own a real estate. Among most of the income ranges and employment of status, the house owner obtains a better condition of loan. By seperating regions of high APR and low APR, the characateristics of defaulted cases in different states can be observed. In the states of higher APR, the majority of defaulted applicants are those who below median monthly income but above median borrowering APR. As for the states of lower APR, the defaulted cases clusters in the area where borrowers below both median of stated monthly salary and borrowers' APR. Another  interesting exploration is that the particularities of defaulted applicants can be seen and listed below:
  a. Part-time / Self-employed / Other / Not-employed / Retired ==> Monhtly income < 5000 & Monthly loan payment < 500
  b. Employed (regardless whether is house owner) ==> Monthly income < 10000 & Monthly loan payment < 500
  c. Full-time (regardless whether is house owner) --> Monthly income < 10000 & Monthly loan payment < 1000



## Key Insights for Presentation

> From the investigaton, I would like to present insights as below: 
a. Most of the borrowers came from CA, reached at more than 12000 people, and the sum of CA applicants are more than the combination of NY and FL. The majority of loan people applied for 36 month, following by 60 months and 12 months
b. Over 68% of the loan applicats are employed, following by 26% of 'Full-time' and less than 1% of 'Part-time'. However, in my view, the questionnaire 'Employed', 'Full-time', and 'Part-time' are quite ambiguious since both 'Full-time' and 'Part-time' can be categorized as employed.
c. The most common purpose of loan is for debt consolidation, reached at more than 56%; 8% of usage of loan is unknown and 7 % is planed to be used in house rennovation. The usage of business achieved more than 5%, compared to less than 3% for vehicles, personal loan, expenses on household, and medical or dental accordingly.
d. The upper and lower range of credit score have the strongest negative correlation with borrowers' APR. That is, the higher the credit score range, the lower the loan cost for borrowers. Several negative correlated factors includes available bankcard credit, the orginal amount of loan, the percentage of trades never delingquent, and monthly loan payment. The utilization of bankcard is relatively positive correlated with borrower annual percentage rate. 
e . People with employment status in "Other" have the highest average APR while those who have full-time, part-time job, not-employed and self-employed have similar level of APR. The trend in general can be observed that the higher the annual salary, the lower the average APR. Surprisingly, for those who are not employed have the same level of APR as people with hieghest annual income. The loan purpose for houshold expense has the highest average APR while personal loan has the least
f. Owning a property is quite helpful to strive for better condition of APR, and a clear trend of gradually decreased APR for house owner can be seen. 
g. In the states of higher APR, the majority of defaulted applicants are those who below median monthly income but above median borrowering APR. As for the states of lower APR, the defaulted cases lies in the area where borrowers below both median of stated monthly salary and borrowers' APR.
h. In both high and low APR regions, a postive correlation between monthly loan payment and monthly inomce can be seen for those completing the loan and work as employed, full time, self-employed, other, and retired. However, the relationship is not so obvious for those who are part-time, not-employed, and defaulted the loan.

