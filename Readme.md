
Lending Club Case Study


Business Understanding

•Consumer finance company is specialized in lending various types of loans to customers. Based on applicant profile, company decides to take below actions. Based on which risks involved are,
•Applicant who is likely to repay the loan
•If profile not validated correctly, its going to be a loss of business for consumer finance company
•Applicant who is not likely to repay the loan
•If profile not validated correctly, approving the loan might lead to financial loss for the consumer finance company
•The loan data set provided contains details about past loan applicants. It has various attributes related to consumer attributes, 
•Loan attributes 
•Applicant profile information including details like their employment details and income etc.
•Consumer attributes


General Information

•Exploratory Data Analysis for loan data set will be conducted by performing below steps.
•Data Cleaning – Data cleaning will be performed to have more meaningful and required data for our analysis.
•Data Understanding - Get an understanding of the loan data set by going through data dictionary and the variables specific usage to see if they are going to contribute for our analysis 
•Univariate Analysis - Analysis for each column to get their data pattern and business understanding by plotting the graphs to read the distribution
•Bivariate Analysis - Analyze two data variables to see if we can get a meaningful insight of those variables
•Segmented Univariate Analysis - Analyzing the continuous data variables with respect to the categorical column
•Conclusion – Solution recommendations
•Provide final conclusion to the problem statement based on final analysis.

Conclusions:
- Shorter the period the number of borrowers are more. The borrower could be a defaulter if the term is lesser and also the term here may represent upcoming loan application related term or the processed loan term.
- Majority of the loan borrowers income is not verified and they are prone to defaulting. Approximately around 20-25% of the borrowers income source was verified but not the income. There is a small percentage of risk that these borrowers can become defaulters. The verified borrowers are completely out of risk for defaulting process.
- There are higher number of loan borrowers as part of grade A & B. Further, the loan borrowers decreases as the grade decreases.
- Debt consolidation related loan borrowers are more.
- As the interest increases the number of defaulters increase. The bank should consider interest rate minimal like the non defaulters while considering loan application processing and this should reduce the number of defaulters. Also, The revolving utilization rate is higher for defaulters based on the high usage of revolving credit.
- As the annual income of the borrower is higher less chances of becoming defaulter. The defaulters are higher with less annual income.
- The loan_amnt/funded_amnt/funded_amnt_inv all have a common trend as the loan_amnt/funded_amnt/funded_amnt_inv are high there are less defaulters. As the loan amount decreases, the defaulters high. It is also observed that, the loan_amnt/funded_amnt/funded_amnt_inv below 10000 has the highest defaulters and exceeding 10000 has the lowest trend.
- There are more defaulters with loan interest rate in the range 5-15%. Higher the interest rate, the tendency to close/pay the loan is higher and also the defaulters are more when the salary range is below 50000. The defaulters are less with increased salary range of borrowers.
- The defaulters trend is observed with every salary range of annual income but their purpose of loan categories are deviating for different range of annual_inc. Irrespective of the annual_inc and purpose of loan applied by borrower, the defaulting risk is high in every purpose and with every annual_inc range.
- The defaulters are more with annual_inc greater than 50000 in loan borrowers categories like
-   home improvement/small        
-   business/house/medical/credit card/wedding/debt consolidation
- The defaulters are more with annual_inc less than 50000 in loan borrowers categories like
-  Car/other/major           
-  purpose/moving/vacation/education/renewable energy
- The borrowers with less loan term are having less defaulters with the loan amount below 10000. As the term is high, the defaulters are more with the increased loan amount trend. The defaulters are anyways high irrespective of term and also the loan amount.
- The defaulters are identified in every category of the verification_status with verified/source verified/not verified. However, its good idea to reduce the loan_amnt as the defaulting risk is high irrespective of the verification_status
- The defaulters are high in every home ownership category. However, The home ownership with mortgage and other categories are having very high defaulters trend. The own and rent home ownership categories are having comparatively less defaulters. Its better to consider the own and rent home categories with a lesser loan amount to reduce the defaulters risk. The mortgage home ownership is having higher loan amount and the high defaulters so, reducing the loan_amnt might reduce the risk of defaulters. As the interest goes high, the defaulters are high in every home ownership category
- As the number of installments increases along with loan amount, there is a high risk of defaulters. With less installments and the less loan amount, we can see there is a positive correlation between the loan amount and installments.
- Higher the annual income with lower loan amount, the defaulters are less as in the loan_amount below 20000 and the annual_inc around 100000 there are less defaulters. To reduce the defaulters risk, the loan amount approved for higher income borrowers can be little lower loan amount than the maximum suggested range today
- The defaulters risk is low with reduced interest rate along with reduced loan amount. The interest exceeding 17.5 % and loan amount exceeding 15000 is not showing a great correlation and it indicates higher risk of defaulters.

