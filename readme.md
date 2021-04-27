# Michigan COVID-19 Demographics Data

This repo is an attempt to gather up all the "Cases by Demographics Statewide" xlsx files that are posted Mon-Sat (excluding holidays) to the Public Use Dataset section of the Michigan Department of Health and Human services page at https://www.michigan.gov/coronavirus/0,9753,7-406-98163_98173---,00.html.

This collection does not appear to include a file representing every non-Sunday and non-holiday date. The state does not maintain a way to find files from previous dates, and the directory containing the files is not browsable. The urls of the files were gleaned by parsing Google search results based on the filename fragment of "Cases_by_Demographics_Statewide_2020" and "Cases_by_Demographics_Statewide_2021".

Also note that the state did not start supplying these public use datasets until June of 2020, shortly after implementing a Microsoft Power BI dashboard. Before June, any demographic data was simply printed as an html table to the state's data page. Those are probably captured or scraped and stored by some other person elsewhere.

I am going to try to script a daily scraping of the state's page to retrieve future demographics xlsx files and deposit them here.
 