# Gabriel Quinteros Berocay
Repository for personal projects

## [Project 1: SUBE personal data scraper and cleaner](https://github.com/Gabeeh94/SUBE-Project)

A Python scraper that access the SUBE's (Buenos Aires's public transportation system) data of a particular person. The output file was then used in Power BI to do some basic analysis and visualizations.


![Power Bi Example](/images/SUBE-Power-Bi.jpg)


## [Project 2: Regression based on the Economic Freedom Index](https://github.com/Gabeeh94/Economic-Freedom-Regression)

¿Is there a relationship between GDP per capita and the economic freedom score of a country?

To answer this question, different regressions taking as a dependent variable (that is, the one we want to explain) the GDP per capita adjuste by purchase parity power and as an independent variable the economic freedom score of the Heritage foundation. For this analysis we used Python and the modules numpy, Pandas, statsmodel and matplotlib.

Final Model:

![Final model](/images/quad regression.png)

 y = 42.9777x² - 3854.5294x + 8.99e+04

## [Project 3: Suicide Rate Analysis using SQL and Python](https://github.com/Gabeeh94/Suicide-Rate)

An analysis of the suicide rate in the world using SQL and Python to clean and extrapolate conclusions from the data including an interactive map, a regression and a classification analysis to see if there is a relationship between GDP per Capita or Sunshine level and the suicide rate.

![Interactive Map](/images/Map.jpg)

## [Project 4: Clustering Analysis: Implementation of K-Modes Algorithm in Python](https://github.com/Gabeeh94/Clustering-Analysis)

For this project, my client provided a database with a number of profiles which had a different set of profiles. The objective was:

-    Clustering the profiles with similar accesses

-    Selecting base profiles for each cluster

-    For each profile that is not a base profile, get a list of all the accesses that differ with the base profile of its own cluster

To complete this I used a machine learning algorithm called "K-Modes" similar to the well-known k-means but used for categorical data, that is, non-numerical data like text, characteristics, etc. All the cleaning and data wrnagling was done with pandas and the graphs with matplotlib.
