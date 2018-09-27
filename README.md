# LendingClub


### Detecting default and missing payments in Lending Club loan data

https://github.com/zhou100/LendingClub

#### Summary of analysis:

* Extracted features from raw lending club loan data containing different types, such as categorial, numerical and time series data, imputed missing data using
multivariate imputation by chained equation (MICE) algorithm.

* Performed feature selection through exploratory analysis.

* Fitted linear regression model with regularization to control for multicollinearity to predict loan interest rate 

* Upon loan initial application, predict whether it will be charge off or default.

* Throughout loan payment period, predict whether next payment will be missing,or whether loan status will be changed in next quarter.




#### Data:

Data from Kaggle Lending Club Loan Data (https://www.kaggle.com/wendykan/lending-club-loan-data)

Complete loan data for all loans issued through the 2007-2015, including the current loan status (Current, Late, Fully Paid, etc.) and latest payment information. The file containing loan data through the "present" contains complete loan data for all loans issued through the previous completed calendar quarter. Additional features include credit scores, number of finance inquiries, address including zip codes, and state, and collections among others. The file is a matrix of about 890 thousand observations and 75 variables. A data dictionary is provided in a separate file. k

