# LENDING CLUB CASE STUDY
<p align="center">
 <img  src="1.png">
</p>


## TABLE OF CONTENTS
* [Overview](#overview)
* [Business Objectives](#business-objectives)
* [Technologies Used](#technologies-used)
* [Conclusion](#conclusion)
* [Recommendations](#recommendations)

<!-- You can include any other section that is pertinent to your problem -->
## OVERVIEW

Working for a consumer finance company Lending Club which specialises in lending various types of loans to urban customers. This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below: Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## BUSINESS OBJECTIVES

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.

Objective is to identify the risky loan applicants at the time of loan application so that such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment. And thus minimise the risk of losing money while lending to customers.


## TECHNOLOGIES USED

Analytical Tool : Python
                  (Libraries : Pandas, Numpy, Matplotlib, Seaborn)
                  
Visualisation   : Python, MS Powerpoint


## CONCLUSION

1. Majority of the consumers are either at the beginning of their career (< 3 years) or have spent a decade in the employment circles thus lending club must launch special products at special interest rates to attract more similar customers thus expanding business
2. Inspite of the fetching better interest rates, Low grade (G to A) loans have the higher probability of default
3. Number of loan issues to consumers from CA, FL and NY to make profits as they fetch better interest rates
4. Borrowers who take loan for Small business loans default more often, thus special interest rates must be considered and the guarantees must be ensured
5. DTI serves as good indictor of loan default thus applicants with DTI > 24 should be rejected or charged very high interest rates  

## RECOMMENDATIONS

APPLICANTS WHO HAVE HIGHER CHANCES OF DEFAULTING ARE THOSE:

WHO TAKE LONGER TERM LOANS (60 MONTHS)
HAVE DTI SCORE > 12
PURPOSE OF LOAN IS SMALL BUSINESS
STAY IN RENTED HOMES 


## AUTHOR
Sibi Rajan 

## References
Image - GettyImages RusselTatedotcom
