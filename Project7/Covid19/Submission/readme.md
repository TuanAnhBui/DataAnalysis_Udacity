# Covid19 Exploratory Analysis
## by Tuan Bui


## Dataset

- The main dataset for the 2019 Novel Coronavirus collected and maintained by [Our World in Data](https://ourworldindata.org/coronavirus). It is updated daily and includes data on confirmed cases, deaths, and testing, as well as other variables of potential interest. The dataset is downloaded from https://github.com/owid/covid-19-data/tree/master/public/data
- Dataset contains the number of nurses per 1000 people can be download from the link https://data.worldbank.org/indicator/SH.MED.NUMW.P3?view=chart
- Dataset contains information about GDP growth can be downloaded from the link https://data.worldbank.org/indicator/NY.GDP.MKTP.KD.ZG
- Dataset contains information about the continent of the counties can be downloaded from https://www.kaggle.com/statchaitya/country-to-continent
- Dataset contains information about GDP can be downloaded from https://data.worldbank.org/indicator/NY.GDP.MKTP.CD

The dataset contains 18417 observations with 25 features in which most of them are numeric variables.

## Summary of Findings

In the exploration, I found the following observations:
- positive cases per million and deaths per million vary in different continents. They are increasing very fast in Europe and much slower in other continents. At the beginning, all continents seem to behave the same until March Europe stands out

- We observe that higher gdp per capita higher the number of cases per million. But this might be because the richer countries have more tests so that they found more positive cases. Since we don't have data of the tests in each country, we can't explain this relationship and this is remaining a hypothesis.

- gdp per capita has little effect on the number of deaths per million, except some european countries having around 40k per capita with high number of deaths per million and this is because of the population ageing. 

- total cases per million and total deaths per million are highly correlated as expected, except for some countries have extremely high death rate and this happens because of the population ageing.

## Key Insights for Presentation

In the presentation, we will focus on two observations that we think they are more interesting:

- the positive correlation of gdp per capita and number of cases per million
- the relation between number of cases per million and number of deaths per million

We will start by introducing the increasing of number of cases and number of deaths over time and how continent jump in the analysis. And then explain the interesting relationship between gdp per capita and number of cases per million.

Afterward, we introduce the association between two features of interest which are total cases and total deaths per million. It is reasonable to believe that there should be high correlation between the two but the data show that it's not really. And then we introduce the explanation of that problem by looking at the population ageing. 
