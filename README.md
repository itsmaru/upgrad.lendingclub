# Project Name
    Lending Case Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### The study is based on historical transaction loans, which record the variable that determines if a customer will pay back their loan or not
- This Case study is an analysis consumer data finance/lending company to avoid risk on that company. here type of risks are associated with the bank's decision :
    - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

    - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- Data set contains all loans processed by the Lending house
- Hereby two types of decisions that could be taken by the company:

        the Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

        Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
### Important Aspects of the Dataset
- Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

-  Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

- Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Several factors are found to be able to help identify the risk for default. Higher loan interest rate, longer loan term, higher dti ratio and higher funded amount shows a higher tendency for default.Others factor such as purpose of loan and home ownership although does not show a strong indicator for applicant default or not, should also be taken into consideration when approving for loan


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - 1.4.1
- numpy - 1.22.3
- matplotlib - 3.5.1
- seaborn - 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [itsmaru](github.com/itsmaru) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project --># upgrad.lendingclub
