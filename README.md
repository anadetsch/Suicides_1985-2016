# Suicides, let's talk about it!

Project module 02
- Ana Paula Detsch
- Andreas Glassl
- Alejandro Ugarriza

Data Analysis 03-20, Berlin, 04/30/2020


## Content

- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description

Suicide rates worldwide are alarming, but some countries stand out with numbers that cannot always be explained by simple factors such as economic variation.
During this project we did take a closer look at OECD member countries and analyze a possible relationship between the economy and suicide rates.
Countries in Asia stand out and among them the main one is the Republic of Korea.
During the process, we covered economic information for Korea and the relationship between GDP per capita and suicide rates. The same was analysed for Japan and Russia. 


## Questions & Hypotheses

Does economic growth have any influence on suicide rates?
What is the correlation between suicides of different age groups and the economy? 
Does poverty rates (distribution of wealth) has any influence?
What can make the suicide rates decrease? 


## Dataset

The dataset which was used at the entry point into our investigations is the suicide rates overview from Kaggle:

https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016

Other sources of information:

https://www.kaggle.com/marcospessotto/happiness-and-alcohol-consumption
https://www.ncbi.nlm.nih.gov/books/NBK223752/
https://www.teoalida.com/world/southkorea/
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4691784/
https://bpr.berkeley.edu/2017/10/31/the-scourge-of-south-korea-stress-and-suicide-in-korean-society/
https://en.wikipedia.org/wiki/Poverty_in_South_Korea
https://en.wikipedia.org/wiki/List_of_average_annual_labor_hours_in_OECD_countries
https://data.oecd.org/socialexp/pension-spending.htm
https://data.oecd.org/inequality/income-inequality.htm


## Workflow

1. Brainstorming and Alignement on topics and possible questions
2. Research of relevant data from different sources 
3. Comparing data sources and decision about which dataset to use
4. Extracting and cleaning the data
4. Merging the data
5. Data Analysis
6. Data visualization 
7. Preparing the Presentation 


## Organization

We organized our project by using a trello-board and assigning to-dos to everyone. We had fixed check-ins to discuss problems and share results.

### Notebooks organization

1. Read in the nessessary information from the suicide rates and adding continent information to get a closer look at the statistics.

2. Since most other information was contained with the 3-letter country-codes, a dictionary was added to put the codes into country names in order to be able to merge further information into our main dataframe.

3. Adding relevant economic information for different countries.

4. Looking into alcohol consumption for different countries.

5.-7. Getting a closer look at the suicide rates in perspective to alcohol cunsumption, GDP and health expenditure as well as gros poverty of the countries. Since a lot of information was not accurate/available, we turned to a subset of countries: OECD

8. Subsetting OECD countries and obtaining more information on those on the OECD website such as:
        - poverty rates
        - poverty gap
        - pension inequality
        
9. For Korea taking a deeper look into poverty by age groups and the working hours of different OECD countries (to figure out, if maybe stress might be another measurable factor)

10. All this information was put into one dataframe to visualize the obtained information using Tableau.
-->  https://public.tableau.com/profile/ana.paula.detsch#!/vizhome/SuicidesinKorea/Story1


## Links
[Repository](https://github.com/anadetsch/Suicides_lets_talk)  
[Slides](https://public.tableau.com/profile/ana.paula.detsch#!/vizhome/SuicidesinKorea/Story1)  
[Trello](https://trello.com/b/KZf2rOhN/red-squirrels)  

