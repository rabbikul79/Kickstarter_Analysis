# Kickstarting with Excel
- A project to determine how different campaigns performs in relation to their launch dates and their funding goals
## Purpose
- A project to determine the data driven result to launch a campaign for a play
## Analysis and Challenges
- Used a dateset file name "Kickstarter_Challenge.xlsx" to prform the analysis. First converted the unix time stamped "launched_at" column to date format in a new coliumn "Date Created Conversion"(Column S) Then extract only the year ant placed in a new column "Years"(Column T)
- Added new sheet with the name "Theater Outcomes by Launch Date". Created a pivot table filtered by "Parent Category" and "Years". Placed "Date Created Conversion" data on Rows dispalying only months. Put the the "outcomes" data in the columns section and then displayed Values by the Count of "outcomes" values. Then created a line chart to dispaly those pivot table filtered data.
- Added new sheet with the name "Outcomes Based on Goals". On this tab created 8 columns and 12 rows. Calculated number of diferent project number based on successful, Failed & Canceled using the 'Countifs() function. Calcuated percantage of the diferent project outcomes based on the total project seperated by diferent porjet goals amount section. Then created a line chart showing relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.
### Analysis of Outcomes Based on Launch Date
1. Mejority of the successful campaign luanches during the May & June months. The ratio of of successful campaign is 2:1 over the failed ones.
2. After July the success rate starts to drop and during end of the year almost 1 out of every campaign fails.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85530486/121771598-50dcf180-cb3e-11eb-9836-64280a71da01.png)
### Analysis of Outcomes Based on Goals
1. Lower budgeted campaigns shows more success rate. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85530486/121771686-dc568280-cb3e-11eb-957e-960260a337db.png)
### Challenges and Difficulties Encountered
- Some of the data fileds conatined too much data which were not needed for research. Had to modify the the existing data.
## Results
* Campaign should be launched around May - June period. 
* The campaign goal should be kept within the 5k range to ensure higher possibility to make it a successful one 
### Limitations of this dataset
* Some of the data were not properly catagorized. Some of the data are out of range to make the dateset skewed.
### Other scope
* We could compare similar play in different countries success/ failed rate to figure out the favorate genre for that region and start campaign for those types of plays.
