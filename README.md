# Project Name : Lending club case study
Lending Club provides loan based of  “creditworthiness," Once Lending Club determines that an applicant is “creditworthy,” it issues the applicant an “A” through “G” grade and a 1 through 5 subgrade based off of an applicant's credit history. This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. This project using data analysis tries to find the potential attributes for loan default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Lending Club enables borrowers to create loan listings on its website by supplying details about themselves and the loans that they would like to request.  On the basis of the borrower’s credit score, credit history, desired loan amount and the borrower’s debt-to-income ratio, Lending Club determined whether the borrower was creditworthy and assigned to its approved loans a credit grade that determined the payable interest rate and fees. The standard loan period was three years; a five-year period was available at a higher interest rate and additional fees. Personal loan up to $ 40,000 and Business Loans ranging from $ 5,000 to $ 500,000 are provided
- Background
The project is being submitted as partial fulfilment of Advanced Certificate in Machine Learning and Deeping Learning course conducted jointly by IIIT, Bangalore and Upgrad.
- Business Problem 
Lending loans to ‘risky’ applicants, who are likely to default ,  is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
How consumer attributes and loan attributes influence the tendency of default.
Identify risky loan applicants who are likely to default.  Identification of such applicants using EDA is the aim of this case study.
- Dataset Used
Loan.csv
The data given contains the information about past loan applicants and whether they ‘defaulted’ or not.  It contains the complete loan data for all loans issued through the time period 2007 t0 2011.



## Conclusions
- Loan having Interest rate greater than 15% has high chances of charged off.
- Loan Grade "F" and "G" have very high chances of charged off.                               
- Low Income range between 0 and 20000 has high chances of charged off.
- Small Business applicants have high chances of getting charged off.
- Charged off percent is high where 1 or 2 derogatory public records exist.
- Charged off percent is high where 1 or 2 public record bankruptcies exist.

## Technologies Used
Python 	3.8.8
Pandas 	1.2.4
Numpy 	1.20.1
Matplotlib 	3.3.4
Seaborn 	0.11.1


## Acknowledgements
This project was inspired by IIT, Bangalore and Upgrad, Bangalore..
- References if any...
https://en.wikipedia.org/wiki/LendingClub
https://www.lendingclub.com/
Python Documentation
Upgrad Study Material
https://corporatefinanceinstitute.com/resources/knowledge/finance/fico-score/
https://corporatefinanceinstitute.com/resources/knowledge/credit/purpose-of-credit-risk-analysis/
https://corporatefinanceinstitute.com/resources/knowledge/finance/debt-to-income-ratio/
https://stackoverflow.com/
https://pbpython.com/pandas-qcut-cut.html



## Contact
Created by [@githubusername] 
