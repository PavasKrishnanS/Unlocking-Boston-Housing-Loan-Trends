This project explores housing market trends in Boston and loan approval factors using Regression Modeling techniques.

Linear Regression is used to predict Boston housing prices based on economic and environmental factors.
Logistic Regression is applied to loan approval prediction, analyzing how different financial and personal attributes influence loan decisions.


Boston Housing Price Prediction (Linear Regression)
Dataset Overview
The Boston Housing Dataset consists of 14 features, each representing socio-economic and environmental factors affecting home values.

Key Attributes:
CRIM: Crime rate per capita

ZN: Proportion of residential land zoned for large lots

INDUS: Proportion of non-retail business acres per town

RM: Average number of rooms per dwelling

LSTAT: Percentage of lower-status population

MV: Median Home Value (Target Variable)

Findings
Number of rooms (RM) and LSTAT (lower-status percentage) strongly influenced house prices.

Crime rate (CRIM) and pollution levels (NOX) had a negative impact.

Model performed well with good predictive accuracy.


Loan Approval Prediction (Logistic Regression)

Dataset Overview
The Loan Dataset consists of various attributes related to an applicant’s financial profile and demographics.

Key Attributes:

Age: Applicant’s age

Time_at_address: Duration at current residence

Res_status: Residence status (Owner/Renter)


Occupation & Job_status: Employment type


Time_employed: Years of employment

Balance: Bank account balance

Decision: Loan Approval (Accept/Reject) (Target Variable)

Findings
Key Factors Influencing Loan Approval:

Higher Account Balance increased approval chances.

Longer Employment Duration positively impacted approval.

Applicants with unstable job status (e.g., unemployed) had lower approval rates.

The model achieved good accuracy, correctly classifying most loan applications.


Key Takeaways:

Housing Market Insights: The model identified crucial factors influencing home prices.

Loan Approval Trends: Applicant’s financial stability played a critical role in loan approval decisions.
