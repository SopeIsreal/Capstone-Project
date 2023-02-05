Covid-19 Capstone Project overview

This project attempts to analyze the impacts of the pandemic on the country by creating insights from data science techniques, analytical skills and visualizations 
The analysis shows the following
The part of the country most affected by the virus
The states with the most confirmed cases and casualties
The relationship between confirmed cases and population in each of the States
The daily infection, recovery and death cases in each state
The impact on the Nigerian GDP
The consequences of the change in the national budget that happened as a result of the pandemic.
The relationship between the vulnerability index and the number of confirmed cases

DATA SOURCES AND METHODOLOGY
I would like to state here that this project was a little bit chaotic because the website of the Nigerian Centre for Disease Control, which is the official/sole source of up to date data regarding covid-19 in Nigeria has had issues for a number of months apparently. The data from that site couldnt be used due to this so I had to use the provided but not up to date data given in the project instructions. The faulty NCDC site also feeds the John Hopkins University site which gives data on the daily statistics so that data was also affected. So I had to use data up till 4th of August 2021 for that data set.
As hinted above the data for this project is gotten from different sources and combined to do the analysis from which we infer the insights. Here are some sources of the data:
The Nigeria Center for Diseases Control (NCDC) monitors the country’s COVID-19 situation, and releases data on metrics across all the 37 states in the country. Data from NCDC 	COVID-29 official website (www.covid19.ncdc.gov.ng) 	was obtained by performing a web extraction/ web scraping. This was done by querying the website API and passing the data into a pandas 	DataFrame using pd.read_html().  However, like I earlier stated, this source is unavailable for now because the site is down
Nigeria Community Vulnerability Index Data: The vulnerability index was computed by considering several factors such as socio-economic status, population density, housing type, transportation, epidemiological, health system etcThese factors are known as themes. Each theme was broken into subthemes, and data was gathered from them to compute the overall vulnerability index score by weighing each theme equally. The Overall Vulnerability Index (CCVI Index) refers to the measure of the impact of the virus on a community after the virus arrives. It ranks from Very Low (0) to Very High  (+1). Resource link – here
The Johns Hopkins University Data: The Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE) publishes daily data on confirmed, death and recovered cases across different countries. The data for Nigeria was accessed from the data repository, analyzed and insight was created from the data. Resource link- here
Real Domestic Gross Product Data: The data on Domestic Gross Product (GDP) for Nigeria was provided with the project details. This data was used to determine the impact of COVID-19 on the economy by comparing the Real GDP (Pre COVID-19) with Real GDP (During COVID-19). The analysis was done by plotting the GDP of each year (by Quarter) to show the difference and determine the impact of the negative virus on the economy Resource Link - here
State Budget Data:
States across Nigeria reduced their initial budget due to the impact of COVID-19 on the economy. The budget data was provided with the project details. This data was analyzed to determine the negative impact of the virus on the economy. This analysis was done by calculating the difference between the initial and new budget of each state and calculating the percentage difference. The map of the percentage difference is then plotted to show the change in budget and comparison between the states.


FUTURE WORK SUGGESTION
I would suggest either the recommendation of a more reliable site than the https://covid19.ncdc.gov.ng/ or another project entirely because the main datasource (https://covid19.ncdc.gov.ng/) feeds other data sources like the John Hopkins University site. In most websites that provide the updated covid-19 data for Nigeria, the faulty ncdc site is where it is sourced from. I also would strongly suggest further study of the daily confirmed cases in the country and each region, in comparison with global cases to study the pattern of waves of the infection to prevent another wave and put preventive methods in place.
Also, the mode and method of recording confirmed cases in the country should be looked into to ensure accuracy especially in the Northern region of the country.
