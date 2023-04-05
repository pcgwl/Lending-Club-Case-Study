# Project Name:Lending Club Case Study
Lending club is the largest online loan marketplace, facilitating personal loans,
business loans, and financing of medical procedures.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
In this case study, apart from applying the techniques we have learnt in EDA, we will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
### Project Background
We are working for a consumer finance company that specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business for the company

2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

### Project Statement

Find the driving factors which lead to the defaulted loans which are the major source of loss for the company.

### Data Set

The data set is a CSV file with the loan data for the Lending Club.

## Conclusions
- Major Driving factors which can be used to predict the chance of defaulting and avoiding Credit Loss:
  1. DTI
  2. Grades
  3. Verification Status
  4. Annual income
  5. Pub_rec_bankruptcies
- Other considerations for 'defaults' :
  1. Burrowers from large urban cities like California, new york, texas, Florida, etc.
  2. Burrowers having annual income in the range of 50000-100000.
  3. Burrowers having Public Recorded Bankruptcy.
  4. Burrowers with the least grades like E, F, and G indicate high risk.
  5. Burrowers with very high Debt to Income value.
  6. Burrowers with working experience of 10+ years.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.4.4
- NumPy - version 1.21.5
- Seaborn - version 0.11.2
- MatplotLib - version 3.5.2
- Plotly - version 5.9.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is a case study and is part of the Machine Learning and Artificial Intelligence courses from upGrad and IIITB..


## Contact
Created by [@pcgwl] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
