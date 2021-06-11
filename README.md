# Examining Gun Violence in NYC from 2006-2020
## Did the propensity of NYPD's controversial Stop-And-Frisk policy curtail gun violence?

#### I explore NYPD's own dataset of every shooting incident reported in two parts: 2006-2013, and 2013-2020. The year 2013 marks the official disbanding of Stop-and-Frisk, and I aim to see whether there is a statistically significant difference in murder rates before and after this time period. 

## Background
#### Stop-and-Frisk is a controversial policing method practiced by the NYPD from 2002 to 2013, where officers stopped and frisked individuals they thought posed a risk of carrying a weapon. It has since been disbanded because of the racial profiling it proliferated. However, supporters of the Stop-and-Frisk program argue that it is instrumental in preventing gun crime - specifically murder. I wanted to see if there was any statistical truth to that claim. 

## Data and Exploratory Data Analysis
#### I utilized the City of New York's public data resources to acquire [NYPD's historic dataset of every shooting incident reported between 2006 and 2020](https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8). Additonally, I used [NYPD's historic dataset of every stop and frisk event reported](https://www1.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page) to track the number of stops made through the time period of interest. Lastly, I used this [public geospatial dataset of the city](https://data.beta.nyc/dataset/pediacities-nyc-neighborhoods) to accurately map out locations. 

 
#### In exploring the shooting incident dataset, I found that of the total 23,568 shooting incidents reported from 2006 - 2020, 4488 were murders. Most of these shooting incidents, unsurprisingly, happen in low-income areas. Additionally, I noticed that the year 2013 seemed to be an outlier, and registers as having the lowest rate of murder throughout this time period. By using the coordinates included in the dataset, I was able to map out every incident and murder and visualize the geographical distribution of these incidents.

![City-Wide Map](./images/City-Wide.png)


