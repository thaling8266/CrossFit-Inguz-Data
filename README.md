# CrossFit-Inguz-Data
Visualizes data scraped from CrossFit Inguz website.

##Introduction:

This report uses data scraped from crossfitinguz.com. CrossFit Inguz publishes a WOD (Workout of the Day) to their website daily. The dataset for this report includes WOD data from 1/1/2020 to 2/28/2022 (790) days. For a variety of reasons, there are fifty days where WOD data is missing (i.e., the webpage did not exist) which may affect some analysis within this report.



I've used the Requests Python package to make an HTTP get request from crossfitinguz.com and the Beautiful Soup package to parse the html of the response. Lastly, I used pandas to wrangle the data into a useable data set to produce the visuals for this report. This was done using Jupyter Notebook.
