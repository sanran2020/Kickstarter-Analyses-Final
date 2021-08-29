# Module 1 Challenge - Kickstarter Challenge 
#
## Overview of the project
#### The client is trying to evaluate the likelihood of fund raising success for her play named "Fever". The data being used for the analyses consists of prior fund raising events, including the theaters/plays category that will be used for assessing the likelihood of success. There were two questions to answer towards this - a) Theater Outcomes based on Launch date b) Outcomes based on Goals  
#
## Analyses and Challenges
### Analyses - 
#### a) Theater Outcomes based on Launch date - The analyses involved filtering the original data set to theater (category) and plays (subcategory), followed by creating a pivot table summarizing fund raising events that were successful, failures and cancellations by month. The data here showed that while cancellations and failures were independent of the month they were kicked-off, successful fund raisers showed better outcome in late spring/summer, peaking in May.

<img width="502" alt="Monthly outcomes" src="https://user-images.githubusercontent.com/89116627/131237466-ba1bdade-7bf0-4f33-8bc4-80d2d1f1e923.PNG">

#### b) Outcomes based on Goals - The analyses here required to create a subset table of the category (theater) and subcategory (plays) of interest. Following this, a table with goals/$$ (as buckets) needed to be created using which the total # of plays in successful, failure and canceled was calculated for each $$ fundraising bucket. The calculation was done using COUNTIFS formula and the percentages were calculated. The data showed that for the fund raising amount Louise is asking, the changes of success is ~55%. 

<img width="488" alt="Goal outcomes" src="https://user-images.githubusercontent.com/89116627/131237482-4b61dd1c-0c68-4664-8482-18a0934a7b83.PNG">
### Challenges -
#### My challenges were largely Markdown Pad related and Git related. I know this answer is not pertinent to the question being asked. Potential challenges here could be Countifs related given that there are a large number of inputs into the function that deal with cells/ranges as well as strings.
#
## Results
#### a) Theater Outcomes based on Launch date - The data here showed that while cancellations and failures were independent of the month they were kicked-off, successful fund raisers showed better outcome in late spring/summer, peaking in May.
#### b) Outcomes based on Goals - The data showed that for the fund raising amount Louise is asking, the changes of success is ~55%.
#### c) Limitations and suggestions - I wonder if the subcategory plays is sufficient or there could be further granularity. E.g.: a) Type of play b) Casting. Additional analyses could include separating the outcomes by country and year.
