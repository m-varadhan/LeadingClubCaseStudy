# Upgrad Lending Club Case Study

By
* Varadhan Mariappan
* Vijayamma Battala

1. Data Understanding
2. Data Cleaning
3. Univariate Analysis
4. Segmented Univariate Analysis
5. Bivariate Analysis
6. Correlation Analysis
7. Recommendations

# 1. Data Understading
### 1.1. Problem Statement
A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 

Two types of risks are associated with the bank’s decision:
* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

### 1.2. Business Objectives
* Identification of such applicants using EDA is the aim of this case study.
* Identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.
* The company wants to understand the driving factors (or driver variables) behind loan default. The company can utilise this knowledge for its portfolio and risk assessment.
  

### 1.3 Understanding datasets

#### 1.3.1 Finance attributes
- **loan_amnt** - Amount of money applied for the loan
- **verification_status** - Lender have verified the customer demographics for loan sancation
- **int_rate** - Loan interest rate charged by bank for the customer
- **installment** - Number of monthly installment to repay the loan
- **pub_rec** - Number of derogatory public records which can potentially lead to defaulting the loan.
- **pub_rec_bankruptcies** - Number of locally available bankruptcy record for the customer, indicates the loan to be defaulted.
- **grade** - Rating provided based on credit score indicating the risk
- **purpose** - Purpose of loan categorically differentiated
- **issue_d** - The month which the loan was funded
- **loan_status**
    * **Fully Paid** - Customer have fully paid the loan amount
    * **Current** - Customer who are currently paying the loan amount (non-default)
    * **Charged-off** - Customer who have not paid the loan amount and defaulted
es


#### 1.3.2 Borrower attributes
- **annual_inc** - Customer annual income, higher annual income leads to approval for higher loan amount
- **addr_state** - Customer address state can potentionally impact loan approval since it may be related to econoimic growth of the state.
- **emp_length** - Years of experience can lead to higher income, which can lead to higher loan amount approval.
- **home_ownership** - Cusomter owns home or morgaged or rents, can be used for loan approval and to indetify loan risk
- **dti** - Debt-to-income ration ncan be used to understand if customer can pay their debts and pay the loan amount which has been applied. Lower this value the high rate of loan approval success.

### 2. Data Cleaning

#### 2.1.1. Check for header & footer
#### 2.1.2. If there is any empty rows

#### 2.1.3. Check for null values and compare with total rows, to indetify all columns are null values, then need to drop the columns which is not useful

#### 2.1.4. Remove columns having more than 60% of values missing

#### 2.1.5. Remove descriptive columns

#### 2.1.6 Remove Unwanted rows

#### 2.1.6.1 Remove Unwanted rows

#### 2.1.7 Understand and remove unwanted columns which are not useful for analysis

#### Remove the columns which don't have unique values not more than 1 values

#### 2.1.7. Verify Non-numerical values and standardize it

#### 2.1.7.1 Convert the date columns to proper datetime format

#### 2.1.7.2 Remove the '%' from columns having symbols

#### 2.1.7.2 Fix the decimal points round to 2 decimal points

#### 2.1.7.3 Remove strings from numeric variables

#### 2.1.7.4 Replace strings which are says NaN, NULL or NONE etc,.

#### 2.1.7.4 Merge values if they are not having different meaning

#### 2.1.7.5 Replace Null values with relative values

##### Standardize the data and create derived variables for future analysis

#### 2.2 Create derived variables

#### 2.2.1 Add derived value and create drived values categories 

#### 2.2.2 Add month, year and quarter based for the datetime fields

#### 2.2.3 Numerical based derived category

##### 2.2.3.1 Loan Amount Category

##### 2.2.3.2 Annual Income Category

##### 2.2.3.3 Interest Rate Category

##### 2.2.3.4 Exployment Experience Category

##### 2.2.3.5 Term Year Category

##### 2.2.3.6 DTI Category (Debt-to-Income) 

##### 2.2.3.6 Funded Amount Category

##### 2.2.3.7 Funded Amount Inv Category

#### 3. Univariate Analysis

#### 3.1. Univariate Ordered

#### 3.2. Univariate UnOrdered

#### 3.2.1 Univariate UnOrdered Quantitative

#### 4. Segmented Univariate Analysis

#### 5. Bivariate Analysis

#### 5.1 Bivariate Analysis Ordered

#### 5.2. Bivariate UnOrdered

#### 5.3. Bivariate Ordered Quantitative

#### 6. Correlation Analysis

### 7. Recommendations

#### Discussed in Presentation
