# Exploratory Data Analysis of CoVID-19 Mortality Dataset by Our World in Data.org

![](figs/covid19.png)

Dataset sourced form the following [link](https://ourworldindata.org/covid-deaths).

Skills used: Joins, CTE's, Windows Functions, Aggregate Functions, Creating Views, Converting Data Types, Tableau Desktop

## TLDR Tableau Dashboard [link](https://public.tableau.com/app/profile/ahmed.rashed1337/viz/COVIDRetrospectiveEDA/COVIDEDADashboard)

### Tools and Methods

While MS SQL Server Management Studio is the default platform for SQL data analytics, we quickly migrated to Azure Data Studio. The notebook experience in Azure Data Studio allows users to create and share documents containing live code, execution results, and narrative text. Potential usage includes data cleaning and transformation, statistical modeling, troubleshooting guides, data visualization, and machine learning. Jupyter books compile a collection of notebooks into a richer experience with more structure and a table of contents.  In Azure Data Studio we are able not only to use Jupyter books but also create and share them easily via the integrated GitHub functions.

Although ADS does not have the full suite of database management functionality found in SSMS, this is of little consequence since our primary purpose is to extract, transform, load, and explore data. With this emphasis, the power and elegance and integration of the ADS platform easily outweighs its limited DBA tools. SQL Notebooks, a component of Azure Data Studio, is an excellent presentation tool. It allows us to merge markup, text, and code from a wide variety of languages in a single document. In addition to presentation, it can also be a powerful tool for documentation.

### Overview

Governments across the globe have taken different measures to handle the Covid-19 outbreak since it began in early 2020. Countries implemented various policies and restrictive measures to prevent transmission of the virus, reduce the impacts of the outbreak (i.e., individual, social, and economic), and provide effective control measures.

Looking back at the data is necessary in order to examine the long-term effecgs of the pandemic and the responses to it. Retrospective analysis will allow us to determine which government intervention policies were most, and least, effective. In this way, we can learn from our past and support best practices and policies in the future.

### Analysis

From this EDA, we can answer questions like:-
* Which countries had the highest infection rates?
* Which countries had the highest death rates and/or death counts?
* Which countries had the highest vaccination rates?

From preliminary data inspection, we discovered that the countries with hightest infection per Capita were as follows:
Cyprus
San Marino
Brunei
Austria
South Korea
Faeroe Islands
Slovenia
Gibraltar
Martinique
Andorra

Similarly, the countries with hightest death rate per Capita were as follows:
Peru
Bulgaria
Bosnia and Herzegovina
Hungary
North Macedonia
Georgia
Croatia
Slovenia
Montenegro
Czechia

What these two lists have in common is they are smaller, more densely populated countries. This makes sense because the infection and death rate is directly proportional to how quickly the virus spreads. Smaller nations have less infrastructure to promote and enforce social distancing, and at the same time, higher population density means the virus will have many avenues to jump from host to host, affecting large swathes of community in a short time.

When we investigated the countries with the hightest death counts (irrespective of population), we find that the US tops the chart with more casualties than the next two countries combined!
United States
Brazil
India
Russia
Mexico
United Kingdom
Peru
Italy
Germany
France

This unenviable result is due to both the cultural resistance to social distancing, the mixed messages and policies of the federal vs state governments, and the presence of several high-density cities that were hot-spots of contagion.

When we investigated vaccination rates, there was not much difference among the top 10 populous nations. However, there was a slight tendency for autocratic countries like China, Brazil, and Russia to have a faster rate of vaccinations whereas more liberal countries like the United States, Indonesia, and Mexico to have a more gradual accumulation of vaccinations.

### Data Visualization

SQL views were created in Azure Data Studio for subsequent data visualization, using Tableau Public. Link to data dashboard can be found at this [link](https://public.tableau.com/app/profile/ahmed.rashed1337/viz/COVIDRetrospectiveEDA/COVIDEDADashboard).

### Requirements

* Azure Data Studio version 1.45.1
* Jupyter Notebook VS Code: 1.79.2

### Author
Ahmed Lotfy Rashed

Connect with me on [LinkedIn](https://www.linkedin.com/in/ahmed-rashed-12495a20/).
