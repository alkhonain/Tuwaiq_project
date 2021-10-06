# Project Proposal 
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.



# Question/need:
### What is the framing question of your analysis, or the purpose of the model/system you plan to build?
  * forecasting with the book is cancelled or not depending on the data. 
  * understanding the customer book and give status of each grope deponding the country.
  
  
### Who benefits from exploring this question or building this model/system?
  * the hotailes and booking company since they can figure the best choses they can get.


# Data Description:
### What dataset(s) do you plan to use, and how will you obtain the data?
The data that i plan to use is [Hotel booking demand](https://github.com/alkhonain/Tuwaiq_project_one/blob/main/project/project_dataset.csv) and it's date set that contain 119390 rows and 32 columns and i believe that it's will decrease when i clean the data.
### What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?
below is table containing sample of the 32 column, there are multiple columns that i don't thing will help me. i also know what each column data possible values that there are any outliers that need to get an action.

* a sample of data set:

| hotel |	is_canceled	| lead_time | arrival_date_year |	arrival_date_month |	arrival_date_day_of_month |	stays_in_weekend_nights	| stays_in_week_nights	| adults	|	days_in_waiting_list | required_car_parking_spaces |	total_of_special_requests	 | reservation_status |	reservation_status_date |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |  ------------- | ------------- | ------------- |
| Resort Hotel	| 0	| 12	| 2015 | July |	3 |	0	| 1	| 2	| 0 |	0	|	Check-Out	| 2015-07-04 | |

### If modeling, what will you predict as your target?
the predict target will be the is_canceled.

# Tools:
### How do you intend to meet the tools requirement of the project?
answering the above question will need some tools, like python libraries such as pandas, numpy and matplotlib, and using algorithms to do the prediction.
### Are you planning in advance to need or use additional tools beyond those required?
yes, i might use power bi tool to create a dashboard that view the data.


