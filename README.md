# Exploratory Data Analysis of CoVID-19 Mortality Dataset by Our World in Data.org

![](figs/covid19.png)

Dataset sourced form the following [link](https://ourworldindata.org/covid-deaths).

Skills used: Joins, CTE's, Windows Functions, Aggregate Functions, Creating Views, Converting Data Types.

### Tools and Methods

While MS SQL Server Management Studio is the default platform for SQL data analytics, we quickly migrated to Azure Data Studio. The notebook experience in Azure Data Studio allows users to create and share documents containing live code, execution results, and narrative text. Potential usage includes data cleaning and transformation, statistical modeling, troubleshooting guides, data visualization, and machine learning. Jupyter books compile a collection of notebooks into a richer experience with more structure and a table of contents.  In Azure Data Studio we are able not only to use Jupyter books but also create and share them easily via the integrated GitHub functions.

Although ADS does not have the full suite of database management functionality found in SSMS, this is of little consequence since our primary purpose is to extract, transform, load, and explore data. With this emphasis, the power and elegance and integration of the ADS platform easily outweighs its limited DBA tools. SQL Notebooks, a component of Azure Data Studio, is an excellent presentation tool. It allows us to merge markup, text, and code from a wide variety of languages in a single document. In addition to presentation, it can also be a powerful tool for documentation.

### Overview

Governments across the globe have taken different measures to handle the Covid-19 outbreak since it began in early 2020. Countries implemented various policies and restrictive measures to prevent transmission of the virus, reduce the impacts of the outbreak (i.e., individual, social, and economic), and provide effective control measures.

Looking back at the data is necessary in order to examine the long-term effecgs of the pandemic and the responses to it. Retrospective analysis will allow us to determine which government intervention policies were most, and least, effective. In this way, we can learn from our past and support best practices and policies in the future.

### Analysis

From this EDA, we can answer questions like:-
* Which are the 5 most affected countries in the world?
* Which country has the highest death rate?
* Which countries had the fastest accumulation of vaccinations?

### Data Visualization

SQL views were created in Azure Data Studio for subsequent data visualization, using Tableau Public.

### Requirements

* Azure Data Studio version 1.45.1
* Jupyter Notebook VS Code: 1.79.2

### Author
Ahmed Lotfy Rashed

Connect with me on [LinkedIn](https://www.linkedin.com/in/ahmed-rashed-12495a20/).
