# Road Accident Dashboard Using Excel

I will be describing my project on road accidents. Below is my explanation of what I have completed until now.

Dashboard Link : https://1drv.ms/x/s!Ai8Av7z0k4xilymCMNzrO3Zxd9iz?e=Oq57oW

Dash Board![Road Accidents Dashboard](https://github.com/Bensonmoses/Road-Accident-Dashboard-Usng-Excel/assets/87203089/13ccd1b0-4565-4ac2-a8eb-9f4b0819742a)

## Dataset:
I.	Field Names:
The dataset, which contains values for certain factors that correspond to road accidents, was downloaded from Kaggle, as previously mentioned in the objective statement on the specified date.
The dataset is saved as .xlsx with 3.07 million rows and 21 fields. Some of the variables recorded in the dataset are the following:
1.	Accident index – a variable that uniquely identifies each road accident.
2.	Accident Date, Day of Week
3.	Junction Control – the situation of traffic management at the site of the accident.
4.	Junction Detail – the structure of the intersection or joining of two or more roads.
5.	Accident Severity – the scope of damage resulting from the accident, where categories include “serious” or “slight”.
6.	Light Conditions – the level of visibility available to drivers on the road.
7.	Road Surface Conditions, Weather Conditions – a variable identifying whether the road surfaces at the time of the accident were wet or dry due to weather conditions.
8.	Speed Limit
9.	Vehicle Type

## Data cleaning and preprocessing:
With the help of the sort and filter function, all columns were verified that there are no typo errors in any of the cells. To detect the presence of typos in each column, I implemented a formula that interactively references the SORT and FILTER functions to automatically replace cells containing errors with the correct items.
Using the TEXT function, I created new fields named as Month and Year to separate each item already recorded under Accident Date into the month and year of the date of the accident to automate the matching of field items with road accident occurrence. Creating these additional columns for splitting items from an original column into simpler columns makes data visualization even faster and more accurate, reducing the chances of errors due to data misrepresentation.

## Data Analysis:
Pivot tables and charts were built from the data found in the .xlsx file. One of the Pivot tables that I have created computes and displays the total number of casualties corresponding with categories of the field Accident Severity. In addition, another Pivot table computes the total number of casualties corresponding with Vehicle Type. Doing this can improve the detection of any correlations of the number of casualties with specific variables of which we would like to find the strongest factors of accident casualties.

## Data Visualization:
I created additional columns and rows that were not originally found in the downloaded data for the purposes of data visualization. For the variable Accident Severity, for which responses were recorded as fatal severity, serious severity, or slight severity, I created a new column that converts these responses into percentages. Percentages are expressed in the form of a “doughnut” chart. Afterwards, I have constructed a separate Pivot table for cars, as well as a table to compare the casualties of the current year and the previous year. Then, I created a chart that identifies casualties according to the road types of the site of the accident. I created a tree map to categorize casualties by road surface conditions. Finally, one of the “doughnut” charts divides casualties into location and another “doughnut” chart divides casualties into visibility level.

## Dashboard Building:
I have created and named a new sheet as a dashboard and placed some of the boxes required for visualization on the dashboard.

## Filter panel:
With this panel, we can relate the probability of road accidents to factors such as what month of the year it is, and whether the location is urban or rural.

## Data Analysis Sheet Creation:
The data analysis sheet assesses the likelihood of a person experiencing an accident in the future in relation to the factors discussed in this project.

