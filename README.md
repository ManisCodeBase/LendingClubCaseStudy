# Lending Club Case Study
> Analyzing and understanding the factors affecting loan status using data from Lending Club.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
1. This project aims to analyze loan data from Lending Club to understand the factors that influence the status of loans.
2. Background: Lending Club is a peer-to-peer lending company that connects borrowers with investors. The dataset includes information on loans, borrower details, and payment status.
3. Business Problem: The objective is to identify key variables that predict loan default, which can help in making informed lending decisions.
4. Dataset: The dataset used in this study is the 'loan.csv' file from Lending Club, containing information such as loan amount, interest rate, annual income, and loan status.

## Data Cleaning
- The dataset was loaded using pandas and inspected for missing values and data types.
- Columns with a high percentage of missing values (threshold set at 40%) were dropped.
- Unnecessary columns such as 'id' and 'member_id' were removed to streamline the analysis.


## Univariate Analysis
- Distribution plots were generated for numerical variables to understand their distributions.
- Count plots were created for categorical variables to visualize their frequency distributions.


## Bivariate Analysis
- Box plots were used to examine the relationship between numerical variables and loan status.
- Count plots were utilized to explore the relationship between categorical variables and loan status.


## Multivariate Analysis
- The correlation matrix of numerical variables was computed and visualized using a heatmap to identify significant correlations.


## Feature Engineering
- Debt-to-Income Ratio: A new feature 'dti_ratio' was created by dividing the annual income by the loan amount.
- Employment Length: Employment length was converted to a numeric format to facilitate analysis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1: Higher loan amounts are associated with a higher probability of loan default.
- Conclusion 2: Borrowers with lower annual incomes are more likely to default on loans.
- Conclusion 3: Longer employment length generally correlates with better loan performance.
- Conclusion 4: The debt-to-income ratio is a significant predictor of loan status.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - version 1.x
- matplotlib - version 3.x
- seaborn - version 0.x

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the need to understand loan default risk for better lending decisions.

## Contact
Created by [@ManisCodeBase] - feel free to contact me!
