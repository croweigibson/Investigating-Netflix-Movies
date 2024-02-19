# Investigating-Netflix-Movies
![](netflix_logo.jpg)
## Description
A study showcasing data visualization and exploration methods to determine whether Netflix's movie duration times have gotten shorter. I was able to learn about the patterns and features of Netflix movie durations by utilizing Python and its modules for data processing and visualization.
## Datasource
The [data](https://github.com/croweigibson/Investigating-Netflix-Movies/blob/main/netflix_data.csv) used in this project as well as the complete [notebook](https://github.com/croweigibson/Investigating-Netflix-Movies/blob/main/Investigating%20Netflix%20Movies.ipynb)
## Objective
The main objective is to see if netflix movies have gotten shorter over time. 
## Loading the data
I started by installing two Python libraries that'll help with the analysis: pandas and matplotlib. Then I created a dataframe using the CSV file. 
![](creating-dataframe.jpg)
## Subsetting the dataframe
I subsetted the `netflix_df` DataFrame to retain only the rows where the type is reported as 'Movie'.
