# Credit-Card-Payment-Default-Prediction-AV-JH


https://datahack.analyticsvidhya.com/contest/janata-hack/#ProblemStatement



Credit card is a flexible tool by which a customer can use a bank's money for a short period of time. 

Predicting accurately which customers are most probable to default represents a significant business opportunity for all banks. Bank cards are the most common credit card type in Taiwan, which emphasizes the impact of risk prediction on both the consumers and banks. 

This would inform the bank’s decisions on criteria to approve a credit card application and also decide upon what credit limit to provide.



This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005. 

Using the information given, predict the probability of a customer defaulting in the next month.


About Data Source:
Lichman, M. (2013). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.)


**Data Dictionary**

ID	Unique ID of each client

LIMIT_BAL	Amount of given credit (NT dollars):  It includes both the individual consumer credit and his/her family (supplementary) credit 

SEX	Gender (1=male, 2=female)

EDUCATION	(1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)

MARRIAGE	Marital status (1=married, 2=single, 3=divorced)

AGE	Age of the client

PAY_0	Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months, ... 8=payment delay for eight months, 9=payment delay for nine months and above)

PAY_2	Repayment status in August, 2005 (scale same as above)

PAY_3	Repayment status in July, 2005 (scale same as above)

PAY_4	Repayment status in June, 2005 (scale same as above)

PAY_5	Repayment status in May, 2005 (scale same as above)

PAY_6	Repayment status in April, 2005 (scale same as above)

BILL_AMT1	Amount of bill statement in September, 2005 (NT dollar)

BILL_AMT2	Amount of bill statement in August, 2005 (NT dollar)

BILL_AMT3	Amount of bill statement in July, 2005 (NT dollar)

BILL_AMT4	Amount of bill statement in June, 2005 (NT dollar)

BILL_AMT5	Amount of bill statement in May, 2005 (NT dollar)

BILL_AMT6	Amount of bill statement in April, 2005 (NT dollar)

PAY_AMT1	Amount of previous payment in September, 2005 (NT dollar)

PAY_AMT2	Amount of previous payment in August, 2005 (NT dollar)

PAY_AMT3	Amount of previous payment in July, 2005 (NT dollar)

PAY_AMT4	Amount of previous payment in June, 2005 (NT dollar)

PAY_AMT5	Amount of previous payment in May, 2005 (NT dollar)

PAY_AMT6	Amount of previous payment in April, 2005 (NT dollar)

default_payment_next_month	Target Variable: Default payment (1=yes, 0=no)
 

**Evaluation Metric:**

Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

