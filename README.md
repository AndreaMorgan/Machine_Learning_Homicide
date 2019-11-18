![ML_Homicide](

This project looks at new data provided by the FBI Crime Data Explorer, updated in the summer of 2019.
[The first part of the project can be found here.](https://github.com/stace2775/Economic_and_Victim_Data_Analysis)

Source Data:
[FBI Crime Data Explorer](https://crime-data-explorer.fr.cloud.gov/downloads-and-docs)
 
[Final Tableau Presentation of Homicide in Tennessee](https://public.tableau.com/profile/andrea.morgan7582#!/vizhome/ML_Homicide/HomicidePredictingCrimeTrends) 

## Homicide in Tennessee

Using data provided by the FBI, we created our own database for crime data in Tennessee for the years 2007-2018 using PostgreSQL.  We then queried only the data relating to homicide events for those years, and used Tableau for analysis.  

### Machine Learning

Splitting the data into two timeframes, we trained our models using 2007-2017 demographic data of both arrestees and victims.  We then tried to predict the type of crime and type of weapon used in homicides in 2018, based on demographic data for that year.

[Title
