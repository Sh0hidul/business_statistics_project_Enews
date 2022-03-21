# business_statistics_project_Enews
This is the project describes various hypothesis testing. 
## Problem Statement and Objectives
An online news portal aims to expand its business by acquiring new subscribers. Every visitor to the website takes certain actions based on their interest. 
The company plans to analyze these interests and wants to determine whether a new feature will be effective or not. Companies often analyze users' responses 
to two variants of a product to decide which of the two variants is more effective. This experimental technique is known as a/b testing that is used to determine 
whether a new feature attracts users based on a chosen metric.

## Objective
Suppose i have been hired as a Data Scientist in E-news Express. The design team of the company has created a new landing page. 
I have been assigned the task to decide whether the new landing page is more effective to gather new subscribers. 
Suppose, I randomly selected 100 users and divided them equally into two groups. The old landing page is served to the first group (control group) 
and the new landing page is served to the second group (treatment group). Various data about the customers in both groups are collected in 'abtest.csv'.
I will Perform the statistical analysis to answer the following questions using the collected data.

* Explore the dataset and extract insights using Exploratory Data Analysis.

* Do the users spend more time on the new landing page than the existing landing page?

* Is the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion rate for the old page?

* Does the converted status depend on the preferred language? 

* Is the time spent on the new page same for the different language users?

*Consider a significance level of 0.05 for all tests.*

The  idea  behind  answering  these  questions  is  to  decide  whether  the  new  page  is  effective  enough  to  gather  new subscribers for the news portal. 
We will perform the statistical analysis on the collected data to make the business decision.

### Data Description

The data contains the different data related to E-news Express. The detailed data dictionary is given below.

### Data Dictionary
1. user_id - This represents the user ID of the person visiting the website.

2. group - This represents whether the user belongs to the first group (control) or the second group (treatment).

3. landing_page - This represents whether the landing page is new or old.

4. time_spent_on_the_page - This represents the time (in minutes) spent by the user on the landing page.

5. converted - This represents whether the user gets converted to a subscriber of the news portal or not.

6. language_preferred - This represents the language chosen by the user to view the landing page.

Please <a href ="https://github.com/Sh0hidul/business_statistics_project_Enews/blob/main/ENews_Express_business_statistics_project.ipynb">click here</a> to see the details of the code.
