# Sanfrancisco Venues Crime Analytics
## Background
San Francisco is the most densely populated and large city in the state of California. San Francisco is one of the 20 fastest growing cities in the United States. It's estimated that thousands of new residents will call San Francisco home by 2040, and the city Planning Director said that the city would need more than 92,000 more housing units and 191,000 new jobs to accommodate this growth. The Bay Area as a whole will need 1.1 million additional jobs and 660,000 new housing units to provide for an estimated 2.1 million more people who will move to the city by 2040. 
* Source: worldpopulationreview.com/us-cities/san-francisco-population

San Francisco is the nation’s leader in property crime. Burglary, larceny, shoplifting, and vandalism are included under this ugly umbrella. The rate of car break-ins is particularly striking: in 2017 over 30,000 reports were filed, and the current average is 51 per day. Other low-level offenses, including drug dealing, street harassment, encampments, indecent exposure, public intoxication, simple assault, and disorderly conduct are also rampant.
* Source : https://www.city-journal.org/san-francisco-crime

## Problem Statement
Burgeoning growth of business in city with business running round the clock through various establishment spread across the city, its becoming increasingly challenging for the San Francisco to prevent crimes and have a rapid reaction task forces readily deployed for strategic deployment.

To keep the economic engine running that meets the demand of growing population and workforce, San Francisco police department would like to use a smart solution that can give them a demographic spread of various establishment around the city and concentration of reported crimes that can help them deploy its resources in an efficient and timely manner. SFPD would like to see relationship of crimes to concentration of establishment and peak working hours for strategic deployment of police force

## Data Description & Approach

For data around number of crimes in San Francisco, I will be using the 2019 data for crimes along with latitude and longitude that will enable mapping of the crimes to the location for visual analysis of spread of crimes. 

The data will be sourced from DataSF https://datasf.org/?source=post_page--------------------------- as an excel downloadable file.

For data around establishments in San Francisco, I will be using FourSquare data along with its latitude and longitude that will enable mapping of establishments for visual analysis. I will be using Beautiful Soup for web scrapping  with developer credential provided by FourSquare. 

Statistical analysis will be performed to discover and establish pattern on Establishment and Crime type, Day and Time of Crime in relationship with peak hours of Establishment


