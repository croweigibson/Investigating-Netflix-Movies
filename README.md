# Investigating-Netflix-Movies
![](netflix_logo.jpg)
## Description
A study showcasing data visualization and exploration methods to determine whether Netflix's movie duration times have gotten shorter. I was able to learn about the patterns and features of Netflix movie durations by utilizing Python and its modules for data processing and visualization.
## Datasource
The [data](https://github.com/croweigibson/Investigating-Netflix-Movies/blob/main/netflix_data.csv) used in this project as well as the complete [notebook](https://github.com/croweigibson/Investigating-Netflix-Movies/blob/main/Investigating%20Netflix%20Movies.ipynb)
## Objective
The main objective is to see if netflix movies have gotten shorter over time. 
## Loading the Data
I started by installing two Python libraries that'll help with the analysis: pandas and matplotlib. Then I created a dataframe using the CSV file. 
![](creating_dataframe.jpg)
## Subsetting the DataFrame
I subsetted the `netflix_df` DataFrame to retain only the rows where the type is reported as 'Movie'.
![](subset1.jpg)
## Creating a Second Subset
I further subsetted the `netflix_subset` DataFrame to retain only the columns 'title,' 'country,' 'genre,' 'release_year,' and 'duration.'I then saved the resulting DataFrame as 'netflix_movies'.
![](subset2.png)
## Filtering by movie length
I filtered the 'netflix_movies' DataFrame to include only movies with a duration of fewer than 60 minutes.
![](filter_movies.png)
## Iterating Rows
I initialized an empty list called 'colours' to store different colour values. I iterated through the rows of the {netflix_movies} DataFrame using a for loop. I added the relevant colours to the list based on categories like "Children," "Documentaries," "Stand-Up," and others.
![](iterate.jpg)
## Visual Inspection
![](visualizing.png)
## Results and Conclusion
The result of our analysis of Netflix movie durations ended up being inconclusive. The duration of children's movies and documentaries does not appear to have changed much over the years. 
## Future Considerations
- One of the most important steps will be to perform statistical analysis to measure trends and fluctuations in movie lengths. 
- Future analysis should include investigating the relationships between the lengths and genres of movies as it might also reveal interesting trends.
- Consider creating more elaborate visuals and interactive plots to improve the way findings are presented.
- Finally, using machine learning methods to forecast the lengths of movies based on different attributes can add insightful information to the study.
