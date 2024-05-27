# LendingClubCaseStudy
> Lending Club Project case study files are maintened here. Objective of case study is to understand the driving factors (or driver variables) behind loan default i.e. the variables which are strong indicators of default

![Uploading image.png…]()



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Conclusions
Insight1: At higher loan amounts the percent of charged off loans over total loans increased by 5 percentage points i.e. one in every five loans charged off 

Insight2: At higher interest rates, charged off loans  as a percentage of total loans doubled when compared to overall range of data. Three loans in every ten loans charged off, meaning there is correlation between higher interest rate and loan getting charged off

Insight3: When the interest rate is very low, the percent of charged off loans is way to less when compared to the overall range. This means when the interest rate is very low, very few loans gets charged off

Insight4: When the loan term is 60 months, 25% of the total loans  got charged off

Insight5: As the grade of loan moves from A to G, the percentage of charged off loans keeps increasing. While only 6% of the grade A loans ended up in charged off, in grade G over 33% of the loans are charged off

Insight6: In the F5 subgrade, almost 48% of the loans resulted in charged off loans. In these subgrades F5,G3,G2,F4,G5,G1 the charged off loans percentage is very high(more than 33%. At least One in every three loans got charged off)

Insight7: Lending for the purpose of small business turned out to be risky. More than 27% of the total loans resulted in charged off, this is way more than the average of 16%

Insight8: The percentage of charged off loans is around 15% in most cases except DC-7% and NV-22.5%

Insight9: When there is one pubrec, the percent of charged off loans is high when compared to average. The other sample sizes are very small, so not considering them.

Insight10: When there is one pub_rec, bankruptcy, the percent of charged off loans is high when compared to average. The other sample sizes are very small, so not considering them

![Uploading image.png…]()



## Technologies Used
pandas -- 2.1.4

numpy -- 1.26.4

seaborn -- 0.12.2

matplotlib -- 3.8.0

## Acknowledgements
This project is assignment based on Exploratory Data Analysis(EDA) in AI/ML program of upgrad.


## Contact
Created by vidhyadharp@gmail.com, vijaytechfollow@gmail.com, you may contact us.


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
