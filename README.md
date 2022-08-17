# DA_Project1
Exploratory Data Analysis Project 

COVID-19 World Data

Case & Death Rate

Group 5

Rajiv Wickramatne
Angela Alexander Smith
Liam Twomey      


Research Problem 
Governments around the world have responded to the COVID-19 Pandemic in varied ways, but we don’t know what Government measures and living situations where most effective at alleviating the impact the pandemic had. 

Data Set 
Owid-covid-data.csv


Project Breakdown 

Rajiv - Government stringency measures (by index rate) and the effect it has had on death rates, new case rates, etc. This view is to identify the affect on spread and causality rates as policies were put in place by governments to actively reduce the impact of Covid on the health of their citizens. This topic is highly discussed as the cost of implementing these control measures came at the expense of the economy. 

Considerations - Data used should be before vaccinations were introduced to eliminate vaccine caused reductions in Covid related deaths/hospitalisations/cases

Rough hypothesis - stronger measures taken by governments should have reduced the spread rate within their country. Respectively lessen death rates, hospitalization rates.

	
Data:
Stringency_index:


Government Response Stringency Index: composite measure based on 9 response indicators including school closures, workplace closures, and travel bans, rescaled to a value from 0 to 100 (100 = strictest response)
	
https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/index_methodology.md

Possibly include reproduction_rate (infectious rate of COVID)
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3581633

Test:
	Scatter plot stringency index vs deaths,  stringency index vs new cases



Ang -
1) Overview of the problem
Hypothesis
Countries with lower GDP’s, reduced medical services (eg Hospital beds) and a lower life expectancy will show a higher rate of COVID rated deaths. Additionally review the the ageing population against Covid Deaths

Country living conditions (GDP in relation to the amount of hospital beds & medical services 
tempered by life expectancy vs death rates) - percentage of testing rates would be the limitation to the data set when reporting data

2) Your data and modeling approach
Using 'owid-covid-data.csv' create data frame of relevant columns
Country.nunique 
GPD.mean
Hospital Beds
Life Expectancy.mean
Total Deaths.sum
Testing Rate per Thousand
Create Data frame



3) The results of your data analysis (plots, numbers, etc)
Scatter plots with linear regression?
Country GDP vs Life Expectancy
Country GDP vs Hospital Beds 
Country GDP vs Total Deaths
Country GDP vs Testing Rate (to ensure no biases in data)
Exclude outliers from all plots?
Determine the most relevant data


Liam - From when the vaccine was deployed… how effective was it… 
1) Scatter Plot, date and total cases, visualize case spikes. 2) Contrasted with Scatter plot, date and hosp_patients 3) ~ total_deaths_per_million

visualise case spikes

Story 
total_deaths_per_million
Total deaths attributed to COVID-19 per 1,000,000 people. Counts can include probable deaths, where reported.
hosp_patients
Number of COVID-19 patients in hospital on a given day
total_cases
Total confirmed cases of COVID-19. Counts can include probable cases, where reported.

Observations / Commentary on Trends Observed:

As expected we see a positive correlation between the Country GDP & Life expectancy as well as GDP vs Hospital Beds per Thousand. However looking at the data plotting Country Death Rate vs GDP we are not seeing the negative correlation that what was expected as per the hypothesis that you would see higher death rate in less developed countries. We must however note that the data is limited by the accurate reporting from less developed countries on the death rate related to COVID-19. Following this we elected to review how the the aging populations in countries with higher GDP's (and therefore higher life expectancy) impacted the death rate in these countries. What we see is the death rate has a strong positive correlation in the aging population which could lend to the observation that the age of the population is the stronger contibuiting factor to death rate rather than COVID-19. 








