# Understanding the Effect of Containment Measures on COVID-19 Rates
 DS4A Women's Summit group project, Fall 2020
 
 __Team 8__: Klaudia Krawiecka, Vilda Markeviciute, Amaka Okafor, Alina Petrova, and Sade Snowden-Akintunde 
 
A year have passed since the World Health Organization categorized the spread of the COVID-19 virus as a global pandemic. 
Although everyone across the globe has been exposed to the same health threat, epidemiological implications vary greatly from country to country. 
In this project we aim to analyse these variations and to discover which factors influence them.
Several months of data on the worldwide spread of the virus as well as on how governments and healthcare systems counteracted it allow us 
to compare the situation in different countries and to identify factors and strategies that have proven effective in mitigating the pandemic. 
We start by looking at general socio-economic and geographic parameters of each country, such as GDP, population density or climate, and 
then move to analysing the specific anti-covid steps taken by each country. 
We hypothesize that although geographic and economic factors play a certain role in the spread of the virus, 
concrete measures and policies imposed by governments, such as school closure or travel bans, would be the most effective, 
as they would greatly reduce overall population mobility.

The ​goals​ of this report are:
- to understand what measures have been the most effective in decreasing the
number of COVID-19 cases;
- to predict possible outcomes of enforcing specific mitigation measures; and
- to suggest which strategies are best for mitigating the number of new COVID-19 cases.

__Project report:__ https://github.com/DS4All-2020-Team-8/Team8_DS4A/blob/master/Final%20Report.pdf
__Final presentation:__ https://github.com/DS4All-2020-Team-8/Team8_DS4A/blob/master/DS4All%20Team%208%20-%20Final%20Presentation.pdf


### Datasets used in our project

The main resources that we use:
- https://github.com/CSSEGISandData/COVID-19
- https://www.kaggle.com/tarunkr/covid-19-case-study-analysis-viz-comparisons (*time_series_covid19_deaths_global.csv* and *time_series_covid19_confirmed_global.csv*)
- https://github.com/OxCGRT/covid-policy-scratchpad
- https://github.com/OxCGRT/covid-policy-tracker (*OxCGRT_latest.csv* and *oxford.xlsx*)
- https://data.worldbank.org/indicator/SP.POP.TOTL (demographic country-level data *Income_country.csv* and *Population_country.csv*)
- https://data.worldbank.org/indicator/EN.POP.DNST (population density, *API_EN.POP.DNST.csv*)
- https://data.worldbank.org/indicator/NY.GDP.MKTP.CD (GDP, *API_NY.GDP.MKTP.CD_DS2_en_csv_v2_1429653.csv*)
- https://data.worldbank.org/indicator/NY.GDP.PCAP.PP.CD (GDP per capita, *API_NY.GDP.PCAP.PP.CD_DS2_en_csv_v2_1429223.csv*)
- https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker (combined "stringency index" of containment measures, per country per day (https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/index_methodology.md); *covid-stringency-index.csv*)
- https://www.kaggle.com/themlphdstudent/novel-covid19-dataset (*cases_country.csv*)
- https://www.google.com/covid19/mobility/ (the mobility data)
- https://en.wikipedia.org/wiki/List_of_current_heads_of_state_and_government (ruling leaders of each country, *leaders.csv*)
- https://en.wikipedia.org/wiki/List_of_countries_by_average_yearly_temperature (historic average temperature, *temperature.csv*)

Internal data files:
- *unified-data-per-country.csv*: per country data on income, population, density, total number of confirmed cases and deaths, mortality rate 
(no mobility or measurements data, no per day data)
