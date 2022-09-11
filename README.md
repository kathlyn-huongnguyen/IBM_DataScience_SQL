# IBM_DataScience_SQL
## Using SQL and Excel to explore, visualize Chicago census, public schools and crime data for the period 2008-2012


<b> Datasets </b> : City of Chicago Datasets
1. Socioeconomic indicators in Chicago
This dataset contains a selection of six socioeconomic indicators of public health significance and a “hardship index,” for each Chicago community area, for the years 2008 – 2012. A detailed description of this dataset and the original dataset can be obtained from the Chicago Data Portal at: https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2
1. Chicago public schools
This dataset shows all school level performance data used to create CPS School Report Cards for the 2011-2012 school year. A detailed description of this dataset and the original dataset can be obtained from the Chicago Data Portal at: https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t
1. Chicago crime data
This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days. A detailed description of this dataset and the original dataset can be obtained from the Chicago Data Portal at: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2

<b> Tools</b>:
* SQL (MYSQL WorkBench)
* Microsoft Excel 

<b>Results</b>: 
* No correlation between the hardship index and the number of crimes that occurred in a community area
* The number of crimes seemed to have a strong relationship with the rate of misconduct in schools, and a moderate relationship with the total college enrolments. 
*  Most crimes took place in the streets, the majority of crimes were theft

<b> Conclusions </b>:

According to police records, 25% of crime events between 2008 and 2012 were attributed to street segments. The most common type of crime is theft (20%). 

The finding above leads to my hypothesis that crimes were more likely to occur in the community areas with high hardship indexes. However, the correlation between the number of crimes and the hardship index of 77 community areas is weak (0.25). To illustrate, despite the highest hardship index (98), there were 2 crimes that happened in Riverdale. On the other hand, Near North Side recorded 15 crimes while its hardship index is 1. Also, it seems unpredictable that Austin had 43 crimes (the highest among all areas) but Oakland had no at all though their hardship index is 73 and 78, respectively. 
 
Similarly, several indicators from either census data or public schools’ data were considered relevant to the number of crimes that occurred (e.g., per capita income, per cent housing crowded, household bellowed property, per cent above 15 unemployed, per cent above 25 with no high school diploma, total college enrolment, average school safety score, average family involvement score, average leaders score, average teachers score, average parent engagement score, average parent environment score). Except for the misconduct rates and total college enrolment, the correlation of others to the number of crimes that occurred were below 0.3. The rate of misconduct per 100 students is highly correlated with the number of crimes (76%, R^2=0.57). The total college enrolment seemed to have a moderate relation to the crime rate (54%, R^2=0.30). 
 
 

