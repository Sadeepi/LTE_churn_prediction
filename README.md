# LTE_churn_prediction
## Data Cleaning
 
 Check number of records and in the dataset

![Capture40](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/61dd531d-7345-46b0-a2bc-ba1129b749c0)

##

Check duplicates

![Capture24](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/28d3b534-b37a-43a0-9521-7d8d483e833e)
##
Check the null values

![Capture25](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/c174775a-ace4-4152-928c-03fa3f04264b)
##

Drop null values in cleared_time

![Capture26](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/8aeb25a0-50c2-418e-930c-f6c8a72b74fd)

##

## Data Transformation

Cleared_time and reported_time are in object data type.

![Capture27](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/0d8ffd42-61be-499e-adf2-f17a493599a0)

##

Converted cleared_time and reported_time to datatime data type. 

![Capture28](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/362c9edc-f4fa-4da9-a1af-1771553793d9)

##
Clearence_time is a new column created by substracting reported_time from the clearance time

![Capture29](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/933bd8dd-d4d0-4c23-9b47-06f8544c1638)

##
Converted the clearance_time into seconds.

![Capture30](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/704c00d4-7b3d-4a41-a5bb-6b388ef692e4)

##
## Data Visualization 

Almost all of the faults reported in 2022

![Capture36](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/b873d05a-8a8a-4e6e-8adc-dd6c3b4dbfaf)

##

This pie chart visualize the cleared faults percentage in each month

![Capture37](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/ab8565be-2fad-4ba3-93c8-d3140f8122c5)

##

Most of the faults fixed within a one day. 

![Capture33](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/277a6c6d-54ae-4af7-8a08-864794507b35)


![Capture32](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/96181df6-fdf1-4537-81cf-286ed4c41807)

##

92.1% of faults fixed within a one day. 5.2% of faults fixed within a second day. 
![Capture34](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/fcf0c14d-c1ab-4aec-9227-eda968a7f829)

##

More than 14000 customers reported one fault. Approximately 8000 customers reported two faults. 

![Capture35](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/26788af5-04c2-4691-af37-ac23b1ca8684)

##

Most of the faults were reported from '80 - Network' category

![Capture38](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/b1b4cf6f-f292-44ed-974e-16ab21c539f3)

##

Most of the faults were reported from 'NF-MPLS NODE FAIL' and '02-NO SVC-INTERNET' sub_category

![Capture41](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/a2add757-9d2d-40ae-94e2-47fe5d3f862e)

##

Heatmap to get the relationship between quantitative variables. There is no any strong positive relationship between any two variables.

![Capture42](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/6038cf75-c700-460e-a712-8be4777b3740)

##

D03 - CPE and D16 SOFT SWITCH have the highest average clearance time 

![Capture43](https://github.com/Sadeepi/LTE_churn_prediction/assets/86165230/6b231fc7-560b-406b-adee-2ed051d1798b)



