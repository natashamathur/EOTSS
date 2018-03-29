# EOTSS

## SQL Queries

The SQL Queries for the 4 provided questions are stored in the file `SQL Queries`

## Data Analysis

### Introduction

I decided to look into the question of whether health care expenditure has an affect on the rate of drug overdoses. Right now there are both esesential issues, with national debates over topics such as how health insturance should be administered and the best (and most cost effective) way to deal with the opiod crisis. These issues can also be highly localized to each state. 

### Gathering and Cleaning Data

Data was collected from the [Kaiser Foundation](https://www.kff.org/other/state-indicator/health-spending-per-capita/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D) and [Data.Gov](https://catalog.data.gov/dataset/drug-poisoning-mortality-by-state-united-states). The information provided contained additional statistical infromation, but that was pared down to the relevant month and statistic for the years from 2010 - 2014. The overall change in the spending or in the drug poisioning rate was calculated over that time period, and a metric of (1) for a positive change, (0) for no change, and (-1) for a negative change was applied. This is stored in the document `Data Analysis / Consolidated Data`.

Further analysis was done in the file `Data Analysis / R Testing`. 

### Conclusions

The results gathered through the analysis in R and Excel show that there is not a strong correlation between the change in amount of medical spending and the rate of drug overdoses. This is likely because this issue is a complicated one affected by factors beyond medical expenditure, and may need to be studied at a more indepth level, perhaps county by county. 




