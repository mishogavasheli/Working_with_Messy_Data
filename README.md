# Working with Messy Data
## Who gets hired?

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")


#### Table of content:
* [About ptoject](https://github.com/mishogavasheli/Working_with_Messy_Data/edit/main/README.md#:~:text=Result%20as%20sumery-,About%20ptoject,-On%20the%20second)
* [Project Brief](https://github.com/mishogavasheli/Working_with_Messy_Data/edit/main/README.md#:~:text=at%20that%20moment.-,Project%20Brief,-This%20data%20frame)
* [Methodology](https://github.com/mishogavasheli/Working_with_Messy_Data/edit/main/README.md#:~:text=in%20which%20state-,Methodology,-First%20step%20was)
* [Process](https://github.com/mishogavasheli/Working_with_Messy_Data/edit/main/README.md#:~:text=degrees%20are%20required%3F-,Process,-1.Extracting%20words) 
* [Visualizations](https://github.com/mishogavasheli/Working_with_Messy_Data/edit/main/README.md#:~:text=was%20no%20duplication-,Visualizations,-For%20more%20visualisations)
* [Summary](https://github.com/mishogavasheli/Working_with_Messy_Data/edit/main/README.md#:~:text=our%20Tableau%20workbook.-,Summary,-Location_New%20York%20appears)




## About ptoject
On the second week of our study we were given group project and our  main challenge was to use Python to clean, wrangle and generally reshape the data to made it more straightforward to analyse- to visualise what you find in the data you can either export it to a csv, use excel to chart it, or you could explore the capabilities of Python or Tableau to plot the data.  The data was not easy to work with at that moment.



## Project Brief
This data frame was created by Silvia Lu in 2018 For those who are actively looking for data scientist jobs in the U.S. and help them (including me) to better understand the job market, I scraped Indeed website and collected information of 7,000 data scientist jobs around the U.S. on August 3rd. The information that I collected are: Company Name, Position Name, Location, Job Description, and Number of Reviews of the Company (Download the dataset from Kaggle). 
Our main research was about what kind skill, knowledge and education is more requests from companies and in which state




## Methodology
First step was to identify the most repeated word combitinations under the 'position' column. Data Scientist, Senior Data Scientist, Research Analyst, Data Engineer, Machine Learning Engineer came back as the top 5 most used titles.
1. Who gets hired?
2. Which location has the most opportunities?
3. What skills, tools, degrees are required?


## Process
1.Extracting words from the description (finding the code specifically) Once extracted, it’s all in boolean so it didn’t mean much. Creating new columns that show if a word has been mentioned (degrees)
2.Making the data suitable for Tableau. How to read boolean values in Tableau.We had to convert them to numerical so Tableau could read them 
3.Visualizing the data. Grouping columns, since we created multiple new columns so there was a lot of manual work 
Removing noise from location data. We had to make everything uniform so there was no duplication



## Visualizations
For more visualisations check out our [Tableau workbook](https://public.tableau.com/app/profile/misho.gavasheli/viz/getafix_16355158200190/Dashboard1).



## Summary
Location_New York appears to have the most data science related job advertisments, while San Francisco, Seattle, Chicago, Boston, Washington DC all have a large amount of opportunities.
Soft/Hard Skills_Communication and "Statistics appear to be the most desired soft skills. While Python, Excel and SQL are clearly the most desired technical skills that prospective companies are looking for.
Education_If you have hopes and dreams of being a data scientist, then a PHd is common requirement. Data analysts on the other hand require a bachelors degree on average. 
