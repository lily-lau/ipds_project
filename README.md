Isabel Herrera and Lily Lau

Introduction to Programming and Data Science, Fall 2018 (INFO-UB.0023) 

Final Group Project: "An Analysis on Farebox Recovery Ratio"

Hello Anonymous,

Welcome to our little GitHub site! We are two newbie programmers working together on our final programming project to apply our knowledge on SQL, Python and R. In this project, we are analyzing the Farebox Recovery Ratio. Below are the procedures in cleaning, processing, and visualizing our data:

1) Using Python, we downloaded the main table from this page: https://en.wikipedia.org/wiki/Farebox_recovery_ratio 
Please refer to "Data Cleanup".

2) Write Python code to "clean up" this dataset. Please refer to "Data Cleanup".
For Cleanup, we are trying to ensure that:

- All numbers are only numbers
- All currencies are converted to USD
- All fractions as floats 

Due to some formatting complications, we have also made some Data Assumptions:
- For "Year", if given a range or multiple years, we have chosen the earliest one
- For "fare_rate", we have chosen the first dollar amount that appears

3) Write the cleaned up dataset to a local SQLite database called fareboxdb.sqlite. Please refer to "Data Cleanup".

4) Running fareboxdb.sqlite on Terminal, we did some miscellaneous data cleanup. Please refer to "Data Cleanup on SQL".
On the SQLite Database, we have done the following:

- Create new table "flatdb" to shows flat rate system and ratio
- Create new table "nonzerodb" to removes data with no data inputs

4) Access the SQLite database from R, and create the following plots. Please Refer to "Data Visualization". For Visualization, we will show:
 
i. The unconditioned distribution of fare collection rates 

ii. Scatter plot showing farebox ratio versus fare rates (i.e., what it costs to ride) for flat rate systems 

iii. Create a "joy plot" (i.e., facet plot) of the distribution of farebox ratios by fare system

iV. Create a "joy plot" of the distribution of farebox ratios by continent 


5) Run a prediction model of the fare collection ratio on predictors---what did we learn? 
