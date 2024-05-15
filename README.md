# Lending Club Case Study
> Notebook of python that has several commands to apply EDA techniques on the given datasets.


## Table of Contents
* [General Info](#general-information)

* [Technologies Used]
pandas
matplotlib
seaborn
numpy



<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

Data Understanding:
discovery of the dataset's structure, variables, and meaning by reading the data variables and dataset dictionary. Understanding the context of the data, its sources, and how it's organized.

Data Cleaning:
Calculate the precentage of the Missing Values in the dataset.
Eliminate columns with excessively high missing value percentages, as they may not provide meaningful insights.
For columns with acceptable missing percentages, employ imputation techniques to fill in missing data.
Exclude rows with very high missing value percentages to maintain data integrity.
Data Analysis:
Identify applicant-related variables, such as demographics and financial history.
Examine loan characteristics, including loan amount, interest rates, and terms.
Explore customer behavior variables that may indicate creditworthiness or default tendencies.
Exclude rows with 'current' loan status, as they don't provide conclusive default information because only the Charged-off is marked as 'default'.
Focus on customer behavior variables available at the time of application, prioritizing those accessible via credit bureaus for comprehensive analysis.
Recommendations:
Based on our analysis, we can make some suggestions to reduce the risk of loan defaults. These could involve improving how we decide who gets a loan, changing the rules for who can borrow, or using better tools to predict who might not pay back their loans.

Identification of applicants that identified as defaulters (charged-off) that will help the company to take decesions.
- What is the dataset that is being used?
loan data for all loans issued through the time period 2007 t0 2011.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis:
Customer demographics serve as a reliable gauge of a customer's repayment capacity.

- Conclusion 2 from the analysis:
Current systems for loan grading and customer verification appear to be adequate.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.25.2
- Pandas - version 2.0.3
- matplotlib - version 3.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@Maimana-Kowatly] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->