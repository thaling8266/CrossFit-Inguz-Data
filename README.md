# CrossFit-Inguz-Data
Visualizes data scraped from CrossFit Inguz website.

## Introduction:

This report uses data scraped from crossfitinguz.com. CrossFit Inguz publishes a WOD (Workout of the Day) to their website daily. The dataset for this report includes WOD data from 1/1/2020 to 2/28/2022 (790) days.


I've used the Requests package for Python to make an HTTP GET request from crossfitinguz.com and the Beautiful Soup package to parse the html of the response. Lastly, I used pandas to wrangle the data into useable data sets to produce the visuals for this report. This was done using Jupyter Notebook.

## Documents:

This repository holds five uploaded documents. 
The report can be viewed from either the pdf file or the pbix file. 
1) Power BI Export.pdf 
2) Power BI.pbix : Power BI source file
 There are two ipynb files showing python code used to scrape and prepare data.
3) HTML - Parsing and Looping to Build DataFrame of WOD Data.ipynb
4) Flag Columns to Identify Exercises, groupby Date, and Build DataFrame.ipynb

Lastly, there is an xlsx file explaining how exercises have been mapped for reporting purposes. 
5)  Exercise List Dictionary.xlsx
