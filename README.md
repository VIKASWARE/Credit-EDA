# Credit-EDA
Credit Exploratory Data Analysis Case Study
**Problem Statement:**
◾ The loan providing companies findit hard to give loans to the people due to theirinsufficientor non-existentcredit history.Because of that, 
some consumers use it as their advantage by becoming a defaulter. Suppose you work for aconsumer finance company which specialises in 
lending various types of loans to urban customers.
◾ When the company receives a loan application,the company has to decide for loan approval based on the applicant’s profile.Two typesof risks
are associated with the bank’sdecision:
 If theapplicant is likelytorepay theloan,then notapproving theloan results in a lossofbusiness tothe company
 If the applicant is not likelytorepay theloan,i.e.he/sheis likelytodefault,then approving theloanmay leadtoa financial loss for thecompany.
◾ When a client applies for a loan,there are four types of decisions that could be taken by the client/company):
 Approved:The Company has approved loanApplication
 Cancelled:The clientcancelledthe applicationsometime during approval.Either the clientchanged her/hismindabout the loanor insome cases due 
toa higher risk of theclienthe received worse pricingwhichhedidnotwant.
 Refused:The company had rejected the loan(because the clientdoes notmeet theirrequirements etc.).
 Unused offer: Loan has beencancelledby theclientbuton different stages of theprocess.
◾ The data has the information about the loan application atthe time of applying for the loan.It contains two types of scenarios:
 The client with payment difficulties:he/shehad latepaymentmore than X days on at least one of the firstYinstalmentsof the loaninour 
sample,
 All other cases:Allothercases when thepayment is paid on time

**Goal Statement:**
◾ This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for
taking actions such as denying the loan,reducing the amount of loan,lending (to risky applicants) at a higherinterest rate, etc.
This will ensure thatthe consumers capable of repaying the loan are not rejected.Identification of such applicants using EDA is
the aim ofthis case study.
◾ In other words,the companywants to understand the driving factors (or driver variables) behindloan default,i.e.the variables
which are strong indicators of default. The company can utilisethis knowledge for its portfolio and risk assessment
