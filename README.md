# Lending Club case study
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. 
  Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants 
  is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money 
  owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
  If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. 
  Identification of such applicants using EDA is the aim of this case study. In other words, the company wants to understand the driving factors (or driver variables) 
  behind loan default, i.e. the variables which are strong indicators of default. 
  The company can utilise this knowledge for its portfolio and risk assessment.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
	This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. 
	Borrowers can easily access lower interest rate loans through a fast online interface.
	
- What is the background of your project?
	Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). 
	Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. 
	In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
	
- What is the business probem that your project is trying to solve?
	The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.
	The company can utilise this knowledge for its portfolio and risk assessment.
	
- What is the dataset that is being used?
	 The loan.csv dataset and the Data_Dictionary.xlsx files are used as the datasets.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

1. The DTI column has teh lowest correlation with any column
2. The DTI column has a negative correlation with Annual income
3. Total amount, loan amount, installment and total payment, have very strong correlations with each other. Due to the strong correlation between these variables we can analyse just the Loan amount.
4. Month and year issued do not have any correlation with any variable, but it is not expected to have correlation as it is a measure of time. Any correlation which happens would be by chance.
5. Inquiries column also does not have any strong correlation with any other variable.
6. The proportion of 60 month loans getting defaulted is higher.
7. Proportion wise loans with grade D gets charged off the most.
8. Proportion wise loans with grade D3 and D4 which get charged off the most.
9. Higher the interest rate higher is the chance to default.
10. We see higher chances of defaulting in the 0 - 40k bracket, closely followed by 60 - 80k bracket.
11. Higher loan amounts are charged off more. Hence proper vetting and background checks are necessary for higher loans.
12. We see upon checking the percentage of defaulters that small business loans are more likely to default, followed by renewable energy projects.
13. People with 3 years of work experience and 10 years of work experience tend to default more.
14. People on Other Home ownership arrangements have a slightly higher percentage of loan defaulting, but they are extremely less in number. Then come people with mortgaged homes followed by rented accomodationers. Probably because they have a chunk of their income to pay their mortgages or rent which does not leave them with sufficient income to pay off loans. 
15. Year : 
	>> Initial years had a very low number of customers. It shows a higher percent of defaulters but that cannot be considered. 
	>> We see that the number of customers have risen over the years exponentially
	>> 2009 was the year when the defaults were t its lowest. But it increased ever since with increasing customers. 
16. Quarter : 
	>> We see the least number of defaults in Q1 followed by a spike in Q2 and a bigger spike in Q4 after a slight decrease in Q3.
	>> COuld be the holiday season affecting this

17. Month : 
	>> Observations same as the quarters.
	>> The Q2 spike is contributed majorly by May. Analysis needed for the month of May.
	
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas version 1.5.3
- numpy version 1.24.3
- matplotlib version 3.7.1
- seaborn version 0.12.2
- python version 3.11.4


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the EDA module tutorials of the Upgrad AI and ML program.

- This project was based on EDA module, and Data visualization with Python tutorials of the Upgrad AI and ML program.


## Contact
Created by @siddharthr193 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->