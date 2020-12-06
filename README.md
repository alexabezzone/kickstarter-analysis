# Kickstarter Challenge Analysis

## Project Overview 

### Purpose of Analysis

The Kickstarter Challenge analysis project was aimed to help our client Louise understand how other plays' launch dates and funding goals did compared to her play *Fever*. To help Louise observe other plays, the Kickstarter data was analyzed and outcomes of plays based on launch dates and funding goals were visualized. 

## Analysis and Challenges 

### Analysis Of Outcomes Based On Launch Date

In order to analyze the data for play outcomes based on launch date, we first calculated the year from the "Date Created Conversion" column within the Kickstarter_Challenge Excel sheet using the `YEAR()` function. After, a pivot table was created and filtered by "Parent Category" and "Years." The rows of the pivot table were the "Goal" dollar amount of the plays and the columns were "Outcomes" of the plays based on their goal amount. After, a line chart was created to visualize the relationship between the play outcomes and the date at which it was launched. Please see the chart below. 

![Theater_Outcomes_vs_Launch.png](/Users/alexabezzone/Desktop/Data_Bootcamp/Excel_Module 1/Resources/Theater_Outcomes_vs_Launch.png).

### Analysis Of Outcomes Based on Goals 

A new sheet was created in Kickstarter_Challenge to analyze outcomes of plays based on their monetary goals. To populate the goal amount based on the "Number Successful," "Number Failed," and "Number Canceled" plays, the `COUNTIFS()` function was used. After the goal amount based on outcomes column was created, the `SUM()` function was used to calculate the sum of all the projects for each goal amount. The percentages of the outcomes by the goal amount was also calculated. After, a line chart was created to visualize the relationship between outcomes of the play based on the goal amount. Please see the chart below.

![Outcomes_Based_On_Goals](/Users/alexabezzone/Desktop/Data_Bootcamp/Excel_Module_1/Resources/Outcomes_Based_On_Goals.png).

### Challenges of Analysis

There were challenges in the Kickstarter data analysis process. One challenge was that for the analysis of outcomes based on goals, the outcome column contained 0 cancelled plays. This was a challenge because it did not truly represent all of the plays that were cancelled in the past. Therefore, the data may not be representative of the entire population of all Kickstarter plays. This challenge was overcome by acknowledging the lack of cancelled plays and creating a line graph to visualize those plays compared to the number of successful and failed ones. Another potential challenge was the smaller number of plays in the theater category of the Kickstarter_Challenge sheet. The small number of plays could potentially limit external validity. 

# Results of The Kickstarter Analysis

## Results

### Results of Outcomes Based On Launch Date

The results of the outcomes based on launch date analysis was that the most successful Kickstarter plays launched in the month of May. The most failed Kickstarter plays launched within the summer months of May to August. 

### Results of Outcomes Based On Goals

The most successful outcome based on goals was a goal of $1,000 to $4,999 with a 72% success rate. The most failed outcome based goals was a goal of $45,000 to $49,999 with a 100% fail rate. 

### Limitations and Recommendations

## Limitations

Some limitations of the Kickstarter data is that the number of Kickstarter plays within the theater category was smaller compared to the other categories. This could have a potential effect on the external validity of the Kickstarter plays. Another limitation is the limited data on the number of cancelled Kickstarter plays. This could have potentially skewed the outcome data of the plays. 

## Recommendations

One recommendation for future analysis of the Kickstarter data is to include additional tables or graphs and to include more data about the cancelled plays. 

