## Project Name: Data Analysis Baby Step
 
----
## Project Objective: Problem Statement
##### Build an interactive COVID-19 dashboard using Excel to tell a story on COVID-19 to show us the pictorial representation of the top 5 countries with the highest and lowest prevalent cases of COVID-19 and show us cumulative yearly and daily confirmed cases of COVID-19 graphically. 
----
## Data Sourcing
#### The COVID-19 dataset was scrapped from the web into Excel from GitHub. The confirmed, death and recovered cases of the dataset was imported into Excel.
----
## Data Transformation
##### After importing the confirmed, death and recovered cases of the dataset into excel, the data was transformed using power query in excel. The data was a wide data because it is in time series, so we reduced to number of columns to six by selecting the four headers in the column (province, Country/region, lat and long), we right-click on it and unpivot order column, I changed the two remaining columns into date and confirmed. I change the date from text into date. Since the data was imported separately, there was not the need for transforming the other data since it’s power query, the changes were applied automatically. I merged the transformed data (confirmed, death and recovered cases) together. The merged data was loaded into excel to begin the dashboard creation. Pivot table was used to summarize the data in excel using analyze data and the various charts was used in building the dashboard.
----
## Findings and Recommendation
##### Upon importing the data into power query, when we transformed the date from text to date, some part gives an error while some part was transformed into date. I tried all possible way to correct the error, but it was not corrected so I must remove the errors from the data.
