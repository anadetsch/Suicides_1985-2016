# Suicides_1985-2016

The dataset which was used at the entry point into our investigations:

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

# Covering the thought process:

What is influces on people committing suicide? What is the correlation of suicides of different age groups and the

        - economy?
        - alcohol/drug consumption
        - poverty rates (distribution of wealth) 

# Covering the notebooks

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
