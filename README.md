# Movie Analysis Project

Welcome to my Movie Analysis Project repository! In this project, I explore a dataset containing information on the top 10,000 popular movies from Kaggle. My goal is to extract insights from the data, perform data cleaning, and visualize the results in an informative manner.

## Dataset

The dataset used for this analysis can be found on Kaggle: [Top 10000 popular Movies TMDB](https://www.kaggle.com/datasets/ursmaheshj/top-10000-popular-movies-tmdb-05-2023).

## Project Highlights

Here are the key highlights of my analysis:

1. Data Cleaning: I performed extensive data cleaning operations, including dropping useless columns, removing rows with null values, empty genres, empty production company entries, and rows with zero values for runtime, vote average, and vote count.

2. Enriching the Dataset: I added a new column called "Profit" to calculate the profitability of each movie. The profit was derived by subtracting the budget from the revenue.

3. Exporting the Dataset: I saved the cleaned and enriched dataset as a CSV file as 'movies.csv' for easy access and future use.

4. Visualizing Insights: I created visualizations to showcase the following movie categories:
   - Top 10 Highest Budget Movies
   - Top 10 Highest Revenue Movies
   - Top 10 Most Profitable Movies
   - Top 10 Most Loss Making Movies
   - Top 10 Most Popular Movies
   - Top 10 Highest Vote Count Movies
   - Top 10 Highest Vote Average Movies

5. Language Analysis: I analyzed the dataset to determine the distribution of movies based on language.

6. Genre Analysis: For each genre, I listed the 5 most popular and 5 most profitable movies, offering valuable insights into genre-specific trends.

7. Production Company Insights: I identified the top 5 production companies with the maximum number of movies, shedding light on industry leaders and their contributions.

8. Popularity over Time: I visualized the average popularity, vote count, and vote average over time, providing a comprehensive view of changing trends within the movie industry.

9. Financial Trends: I analyzed the average budget, revenue, and profit over time, revealing financial patterns within the film industry.

10. Genre and Language Analysis over Time: I examined the rise and drop of popularity within different genres and languages over time, offering fascinating insights into audience preferences.

## Repository Contents

- `popular_10000_movies_tmdb.csv`: Dataset file in CSV format.
- `data-analysis-and-visualization.ipynb`: Jupyter notebooks used for data cleaning, analysis, and visualization.
- `movies.csv`: Cleaned Dataset file in CSV format.
- `README.md`: This file provides an overview of the project.

## Feedback and Contributions

I welcome your feedback and suggestions for improving our analysis. I believe in the power of collaboration and appreciate your input!
