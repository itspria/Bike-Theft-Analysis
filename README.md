# BIKE THEFT ANALYSIS IN OTTAWA AND VANCOUVER DURING COVID19 

### Team Members
- Priya
- Insiya
- Andriy

### Project Outline
Covid19 has disrupted several industries, and the biking industry is no exception. With several activities not allowed, individuals have resorted to outdoors activities and biking has been a favourite. However, with increased demand many stores have reported low inventory. Simultaneously, there have been increased reports of bike thefts in many cities. 

In Seattle, Wash., there was a 54% increase in reported bicycle thefts. Denver, Colo., has seen around 26% increase in bike theft between 2019-2020, according to the Denver Police Department. As for Boston, Mass., it has climbed from 790 in 2019 to 1015 in the last year, a 28% increase. New York City has similarly seen a nearly 30% spike from March to Sept. 21 of last year when compared to the same period in 2019, according to The New York Times. 

In this project we will explore if similar bike theft trends are observed in Ottawa and Vancouver in Canada. 

### Research Questions

Q1:  Explore if  major cities in Canada (Ottawa, Vancouver) have seen similar trends in bicycle thefts due to COVID19

Q2: Identify the relationship between the bike theft rates and bicycle demand 

Q3: Identify the relationship between the bike theft rates and number of covid cases

### Methodology 
 
Clean data

Q1: 
- Identify monthly number of thefts for two cities for each year (2018 - 2020).
- Thefts on weekdays
- Will use time series graphs to plot theft for each city 
- Calculate key statistics for each city and year
- Bonus: heat map of the theft areas 

Q2: 
- Identify monthly usage / bike trafic  for two cities for each year (2018 - 2020).
- Calculate correlation b/w bike theft rates and usage
- Run regression analysis and plot appropriate graths

Q3:
- Calculate correlation b/w ridership and covid cases
- Calculate correlation b/w thefts and covid cases
- Are red lockdown days have higher/lower thefts/ridership (anyone)


Summarise the results for each analysis, make conclusions, and write a report 

### Datasets Resource
Vancouver
- <https://vancouver.ca/streets-transportation/how-we-collect-bike-volumes.aspx>
- <https://geodash.vpd.ca/opendata/>
- <http://www.bccdc.ca/health-info/diseases-conditions/covid-19/data>

Ottawa
- <https://open.ottawa.ca/datasets/ottawa::bicycle-theft-1/about>
- <https://open.ottawa.ca/documents/f218592c7fe74788906cc6a0eb190af9/about>
- <https://open.ottawa.ca/datasets/ottawa::covid-19-cases-and-deaths-in-ottawa/about>

### Analysis
![Bike Thefts Yearly](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/biketheftyearly.PNG)
![Bike Thefts Monthly](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/biketheftmonthly.PNG)
![Bike Thefts Daily Ottawa](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/dailythefts_ottawa.PNG)
![Bike Thefts Daily Vancouver](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/dailythefts_vancouver.PNG)
![Bike Thefts Maps](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/locations.PNG)
![Bike Volume](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/bikevolume.PNG)
![Bike Thefts Vs Volume](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/theftsvsvol.PNG)
![Bike Thefts Vs Covid-19 Ottawa](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/covid_thefts_ott.PNG)
![Bike Thefts Vs Covid-19 Vancouver](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/covid_thefts_vc.PNG)
![Bike Volume Vs Covid-19 Ottawa](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/covid_vol_ott.PNG)
![Bike Volume Vs Covid-19 Vancouver](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/covid_vol_vc.PNG)
![Conclusion](https://github.com/itspria/BootcampProject1/blob/main/analysis/images/conclusion.PNG)


![WF Image](https://github.com/itspria/BootcampProject1/blob/main/raw_data/WF.PNG)
