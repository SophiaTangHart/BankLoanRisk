# BankLoanRisk

Background:

Banks loan out money to customers to finance a car, a house, pay for education, consolidate loans, etc. Borrowers agree to pay back the money with an interest on a monthly basis. Sometimes, due to unexpected circumstances, some borrowers are not able to pay back the money.

Research Objectives:

The banks would want to see what the pattern is in the customers to predict if a customer can pay back the loan, so the bank knows who to lend out the money. I would like to predict if any customer goes to a bank, should the bank loan out the money to the customer. Looking at it from another perspective, can a person pay off the debt when they consider taking on a loan.

Research Questions:

    What factors contribute/correlate most to bank loan status?

    Can we predict if a borrower will be able to pay the debt in full?

Dataset

The dataset is taken from Kaggle (https://www.kaggle.com/zaurbegiev/my-dataset). There are over 100,000 rows and 19 columns (features) in this dataset. The predicted feature variable is Loan_Status, which is a categorical variable with value either “Fully Paid” or “Charged off”. Fully Paid means the borrower can pay back the debt, while charged off means the borrower is unlikely pay the bank after a substantial delinquent for a period of time. The remainder of the debt is sometimes collected by a third-party agency.

LoanID,

CustomerID,

Loan_Status,

Current_Loan_Amount,

Term,

Credit_Score,

Annual_Income,

Years_in_current_job,

Home_Ownership,

Purpose,

Monthly_Debt,

Years_of_Credit_History,

Months_since_last_delinquent,

Number_of_Open_Accounts,

Number_of_Credit_Problems,

Current_Credit_Balance,

Maximum_Open_Credit,

Bankruptcies,

Tax_Liens
