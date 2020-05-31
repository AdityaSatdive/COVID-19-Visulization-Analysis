# COVID-19-Visulization-Analysis Till 31 May 2020
Context
From World Health Organization (https://www.who.int/emergencies/diseases/novel-coronavirus-2019) - On 31 December 2019, WHO was alerted to several cases of pneumonia in Wuhan City, Hubei Province of China. 
The virus did not match any other known virus. This raised concern because when a virus is new, we do not know how it affects people.
So daily level information on the affected people can give some interesting insights when it is made available to the broader data science community.

Johns Hopkins University(https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6) has made an excellent dashboard using the affected cases data. Data is extracted from the google sheets associated and made available here.






Column Description
Main file in this dataset is covid_19_data.csv and the detailed descriptions are below.
covid_19_data.csv
•	Sno - Serial number
•	ObservationDate - Date of the observation in MM/DD/YYYY
•	Province/State - Province or state of the observation (Could be empty when missing)
•	Country/Region - Country of observation
•	Last Update - Time in UTC at which the row is updated for the given province or country. (Not standardised and so please clean before using it)
•	Confirmed - Cumulative number of confirmed cases till that date
•	Deaths - Cumulative number of of deaths till that date
•	Recovered - Cumulative number of recovered cases till that date
