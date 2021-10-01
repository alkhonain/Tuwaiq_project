# Project Proposal 
The project contain dataset from The Centers for Medicare & Medicaid Services (CMS), is the agency within the U.S. Department of Health and Human Services (HHS).



# Question/need:
### What is the framing question of your analysis, or the purpose of the model/system you plan to build?
  * forcastting the values of the next two years for Denominator and Score for each Facility and its Measure
  * calculate the mean of Denominator and Score for each Measure and compare it to national 
  * obtaining the highest and lowest of the measures and what are the facilities that took the highest and the lowest
### Who benefits from exploring this question or building this model/system?
  * facilities, each one of these facilities can get benefits with this model by check the prediction the next years and how much would they expect to have and the scores of each measure.
  * Dactors, any dactor can get benefits from this model by knwing the persentages of the mesaures.

# Data Description:
### What dataset(s) do you plan to use, and how will you obtain the data?
The data that i plan to use is [Complications and Deaths](project/project_dataset.csv) and it's hospital results for surgical complications and mortality
measures, and i obtain to get it from the CMS dataset website.
### What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?
the dataset contain 92455 rows and 18 column that specify the Facility, city and its State and for each Facility there are 19 meatures such as the hip/knee complication measure, the CMS Patient Safety Indicators, and 30-day death rates.

* a sample of dataset:

| Facility ID | Facility Name | City | State | Measure ID | Measure Name | Compared to National | Denominator | Score | LowerEstimate	| HigherEstimate | Start Date |	End Date |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |  ------------- | ------------- |
| 10001	| SOUTHEAST HEALTH MEDICAL CENTER	| DOTHAN	| AL | COMP_HIP_KNEE |	Rate of complications for hip/knee replacement patients |	No Different Than the National Rate	| 175	| 2.6	| 1.6 |	4.3	|	4/1/2017	| 10/2/2019 |

### If modeling, what will you predict as your target?
the predict target will be the Denominator and Score.

# Tools:
### How do you intend to meet the tools requirement of the project?
answering the above question will need some tools, like python libraries such as pandas, numpy and matplotlib, and using algorithms to do the prediction.
### Are you planning in advance to need or use additional tools beyond those required?
yes, i might use power bi tools to create a dashboard that view the data.


