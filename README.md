# Lending Club Case Study
> A Brief Overview: When consumer finance companies receive loan applications, they must decide whether to approve the loan based on the applicant’s profile. To identify 'risky' applicants, these companies rely on various risk parameters. This project aims to identify such risk factors.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Case Study Collaborators](#case-study-collaborators)

## General Information
### Project Information
This project aims to identify risk factors that predict loan default. 
These insights can inform lending decisions, such as loan approval, amount, and interest rate.  

Two types of risks are associated with the bank’s decision:
• If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.  
• If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.  

### Project Background
Understanding the Lending Process and Risks.  
Consumer finance companies face a critical decision when evaluating loan applications: whether to approve or reject a loan based on the applicant's profile.  

When a person applies for a loan, there are two types of decisions that could be taken by the company:  
* **Loan accepted:** If the company approves the loan, there are 3 possible scenarios described below:  
 * **Fully paid:** Applicant has fully paid the loan (the principal and the interest rate).  
 * **Current:** Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.  
 * **Charged-off:** Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan.  

* **Loan rejected:** The company had rejected the loan (because the candidate does not meet their requirements etc.). 

### Business Objective
The company is a leading online marketplace offering personal, business, and medical loans at competitive interest rates.   
A primary challenge in the lending industry is credit loss, incurred when borrowers default on their loans.  

To mitigate credit loss, this project aims to identify factors that predict loan default. By understanding the characteristics of high-risk borrowers, the company can implement strategies to reduce the likelihood of default, such as adjusting loan terms or interest rates.  

Ultimately, this analysis will contribute to improved risk and portfolio assessment.  

### Dataset
The dataset is the csv file provided which has complete loan data for all loans issued through the time period 2007 to 2011.

## Conclusions
* **Interest rate** is a strong predictor of loan default. Higher interest rates are associated with a significantly higher proportion of charged-off loans.
* Applicants with lower **annual income** are more likely to default on their loans.
* **Loan grade** is a significant factor in determining loan performance. Lower grades (D, E, F, G) have a higher likelihood of default compared to higher grades (A, B).
* **Debt-to-income (DTI) ratio** is positively correlated with loan default rates. Higher DTI ratios are associated with a higher likelihood of default.
* **Public Record Bankruptcies** A history of bankruptcy is a strong indicator of increased loan default risk.

**Driving Factor Variables**    
* Interest rate  
* Loan grade  
* Annual income  
* Debt-to-income ratio  
* Public recorded bankruptcies  

## Technologies Used
- Pandas - version 2.1.4
- NumPy - version 1.26.4
- Seaborn - version 0.13.2
- MatplotLib - version 3.8.0


## Acknowledgements
This project was inspired by UpGrad IIITB Programme as a case study for the Artificial Intelligence Machine Learning course.

## Case Study Collaborators
Created by [@rupa-gattani] [@shilpa-pv]
