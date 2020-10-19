# Predicting Weekly Counts of Death from Influenza/Pneumonia  
<img src="images/Influenza Pneumonia Prediction.png"/>

## Data Collection, Organization, and Definitions  
I have used [Weekly Counts of Deaths by State and Select Causes, 2014-2018 published by the National Center for Health Statistics](https://data.cdc.gov/NCHS/Weekly-Counts-of-Deaths-by-State-and-Select-Causes/3yf8-kanr).
The dataset has data broken by State and it has several causes of deaths including:  Septicemia, Cancer, Diabetes, Alzheimer, Influenza/Pneumonia, Chronic lower respiratory diseases, Other diseases of respiratory system, Kidney, Heart, Stroke and Other symptoms. The total of 14, 094 records in 30 columns. 

## Exploratory Data Analysis  
If the weekly counts of deaths are between 0 and 9 it is suppressed to null and a null flag is raised in the matching column for the particular disease. I have replaced null values with 5 to simplify the calculations.  I have also removed the records giving the total count for all states.  
During this stage I have checked for some tendencies and found out that ***cancer and heart disease are by far the two biggest killers*** as can clearly be visible from the boxplot.
<img src="images/boxplot.png"/>
