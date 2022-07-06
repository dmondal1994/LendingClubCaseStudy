# Project Name
> Lending Club Case Study

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Project Goal
> To identify the bank customers who could turn into possible loan defaulters in the future.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Team Members
- Debasish Mondal
- Sudha G. Lakshmaiah

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Table of Contents
* Data Reading and Importing Requisite Libraries
* Data Cleansing
* Data Extraction
* Exploratory Data Analysis (EDA)
* Observations

<!-- You can include any other section that is pertinent to your problem -->

## Data Reading and Importing Requisite Libraries
- Dataset Name: loan.csv
- Total No. of Rows: 39717
- Total No. of Columns: 111
- Following libraries are used in our analysis.
  - Pandas: For dataframe manipulation and analysis.
  - Matplotlib: For data visualization and graphical plotting.
  - Seaborn: For data visualization and graphical plotting in more sophisticated manner.
  - Warnings: To control warning statements.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Data Cleansing
- Remove Null Valued Columns
- Remove Single-valued Columns
- Remove Irrelevant Columns
- Standardize Data formats
- Remove Outliers
### Now no. of rows = 39717 and no. of columns = 19.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Data Extraction
- Loan status marked as ‘Charged Off’ due to on-time payments of their loan installments is excluded from the provided dataset as there is not much weightage on those customers in the loan defaulter analysis.

### Now no. of rows = 38577 and no. of columns = 19.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Exploratory Data Analysis (EDA)
- Univariate and Segmented Univariate Analysis
- ### Observations
  - The vast majority of people use the loan for debt consolidation purposes.
  - The majority of people's incomes have not been verified by LC.
  - Most people have either a rented or mortgaged home.
  - The proportion of people who fully repay their loans is quite high.
  - The loan has mostly been taken out by people who have worked for at least ten years.
  - The majority of people prefer to repay their loans in 36 month installments.
  
- ### The most possible loan defaulters are -
  - The customers whose income source has not been verified by LC.
  - The customers who have rented home.
  - The customers who have taken loans for debt consolidation.
  - The customers who have been labelled as B5 in terms of loan grade.
  - Customers whose loan amount is between 2948 and 5395 INR.
  - Customers whose invested fund amount is between 4947 and 7421 INR.
  - Customers with an interest rate of between 11 and 13.
  - Customers whose installment amount is between 165 and 240 INR.
  - Customers with an annual income between 31599 and 45399 INR.
  - Customers with DTIs ranging from 12 to 15.
  - Customers with an employment duration of 0 to 2 years.
  - The customers whose number of open credit lines in the borrower's credit file is within 2 to 10.
  - Customers who have one derogatory public record.
  - Customers with a revolving line utilization rate of 60 to 80 percent.
  - The customers whose total number of credit lines currently in the borrower's credit file is between 11 and 20.

- Bivariate Analysis
- ### The most possible loan defaulters are -
  - Customers with an annual income of more than 60,000 INR who are taking out a loan for home improvement.
  - Customers who earn more than 60,000 INR per year and whose source of income has been verified by LC.
  - Customers who have an annual income of more than 60,000 INR and have a mortgaged home.
  
- ### Other important observations are -
  - In the case of possible defaulters, the installment amount is strongly correlated with the loan amount.
  - In the case of possible defaulters, the invested fund amount is strongly correlated with the loan amount.
  - In the case of possible defaulters, the total number of credit lines currently in the borrower's credit file is strongly correlated with the number of open credit lines in the borrower's credit file.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contact
Created by [@dmondal1994] - feel free to contact me!

This project is open source and available under the License --> Creative Commons — Attribution 4.0 International — CC BY 4.0


<!-- Optional -->
<!-- ## License --> 


<!-- You don't have to include all sections - just the one's relevant to your project -->
