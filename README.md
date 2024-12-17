# data_collection_challenge  

This new assignment consists of two technical products.
    Deliverable 1: Scrape titles and preview text from Mars news articles.
    Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

## Deliverable 1  

Using splinter and BeautifulSoup to create an automated browser setup to scrape and obtain
the next data from the Mars News site <'<https://static.bc-edx.com/data/web/mars_news/index.html'>  
There were 15 news links in the site and per instructions are stored in article_list.  

### Deliverable 2  

Imports are splinter, BeautifulSoup, pandas and matplotlib to complete this project.  
Scrape the website with the automated setup and save the Mars Weather table to a data_list
and create a DataFrame mars_df to determine the answers to the questions.
Step 1 Visit the website  
Step 2 Scrape the table  
Step 3 Store the data as a list  
Step 4 Create a DataFrame  
Step 5 Analyze the data  

#### Included Tables and data output  

avg_temp bar chart  
avg_temp_sorted bar chart  
avg_pressure bar chart  
avg_pressure_sorted bar chart  
'mars_temperature_data.csv' to Data_Output Folder  

#### Minimum Temperature

The coldest month is 3.0 with an average minimum temperature of -83.30729166666667°C.  
The warmest month is 8.0 with an average minimum temperature of -68.38297872340425°C.  

#### Atmospheric Pressure  

The lowest pressure month is 6.0 with an average pressure of 745.0544217687075 Pa.  
The highest pressure month is 9.0 with an average pressure of 913.3059701492538 Pa.  

#### Year Length  

The average minimum temperatures follow an up and down pattern with our data beginning at a peak period and ending on the way up.  
and has an outlier spike on the way down to the lowest periods.  
Compare the upper and lower peaks to guage a revolution around the sun appproximately.  
The first upper peak starts slightly around 0 and ends around 750. (750)  
The second upper peak starts < 750 and ends approx 1400. (650)  
The first lower starts around 475 and ends around 1125. (650)  
The second lower starts around 1125 and ends > 1750. (625)  
Average our 4 approximations; (750 + 650 + 650 + 625) / 4 = 668.75.  
This is pretty close to the actual figures per Nasa, <https://science.nasa.gov/mars/facts/>  
Which states there are 669.6 sols and 687 terrestrial days.  