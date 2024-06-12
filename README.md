# Bike Rental Visualization



A website that can be found [Here](https://citibikenyc.com/system-data) provides data containing bike rental information across months and years. This project entails examining bike rental data in the summertime, so data from the months June through September in the year 2023 are extracted. With these original four csv data files (one per month), data preprocessing is conducted. The four csv files are combined together to get one DataFrame that represents summertime data. After this, the original four csv files are examined one at a time and a new DataFrame is created for each file which contains each unique bike station name and the count of how many times each bike station appears per month. These new DataFrames are saved as csv files alongside the summertime DataFrame that was created through combining the original data files. All these csv files are then used by Tableau to create visualizations that answer two distinct questions:

## Question 1: What are the most popular starting stations in summer 2023?

To answer this question, two graphs are created: a bar graph and a map plot. The bar graph shows the top 10 start stations with the highest count of appearances in the summertime csv data file. The map plot shows all the starting stations plotted on a map with the color of each marker dependent on the count. A lower count is represented with a light green color, while a higher count is represented with a darker green color. This map plot shows the location of the least and most active stations to see if geography plays any role in station popularity. 


## Question 2: What are the most popular ending stations in summer 2023?

Two more graphs are constructed to answer this question. The bar graph shows the top 10 ending stations with the highest count and the map plot shows all the ending stations and is also colored according to the station's popularity. A lower count is represented with a dark blue color, while a higher count is represented with a deep red color. 

# Structure of the Visualizations

A story is constructed in Tableau that contains all this information. The first dashboard shows the starting station information (bar graph and map plot) and the second dashboard shows the ending station information (the other bar graph and map plot). Together, these visualizations paint a picture regarding the popularity of bike stations in the New Jersey area. The visualizations can be used to create a possible narrative that attempts to explain the phenomena that seems to be present, which can be read by clicking the link that is embedded in the ending station dashboard.  



