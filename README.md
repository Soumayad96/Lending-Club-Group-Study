# Lending Club Case Study
> LendingClub is a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- When a person applies for a loan, there are two types of decisions that could be taken by the company:
>> 1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:<br>
    1. Fully paid: Applicant has fully paid the loan (the principal and the interest rate)<br>
    2. Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.<br>
    3. Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan.<br>
>> 2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.).<br>


- Business Objectives :
>> 1. Identity the risk of the loan applications
>> 2. Indentify the driving factors or variables for the loan application.

- Data to be analyzed
>> Lending Club dataset provided which contains the complete loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The below conslusions are based on the above analysis based on Fully Paid and Charged Off loans and default rate. Conclusions as follows:
> - Chances of being a Defaulter or getting Charged off is very high when purpose of the loan is for small business.
> - Chances of being a Defaulter or getting Charged off increase with the interest rate of the loans.higher the interest rate, high chances of being charged off and vice-versa.
> - Applicants who have taken a loan for small business and the loan amount is greater than 14k have high probablity of getting defaulted.
> - Applicants who have taken a loan in the range 14k - 16k and taken loan for 60months term have high probablity of getting defaulted.
> - Applicants with from than 8 years more employment experience and applied for loan amount above 14k have high probablity of getting defaulted .


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - PYTHON
- library - PANDAS
- library - NUMPY
- library - MATPLOTLIB
- library - PLOTLY EXPRESS


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@Soumayad96] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->