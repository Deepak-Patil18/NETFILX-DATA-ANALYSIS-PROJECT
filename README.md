# NETFILX-DATA-ANALYSIS-PROJECT
---

## Netflix Data Analysis: Uncovering Movie Trends

This project delves into a dataset of movies to uncover insights into genre popularity, audience ratings, and temporal trends in filmmaking. By cleaning and analyzing the data, this project aims to answer key questions about what makes a movie successful and how the film industry has evolved over time.

### Project Overview

This analysis starts with a raw dataset of movie information, including release dates, titles, genres, popularity scores, and vote averages. The initial phase focuses on data cleaning and preparation to ensure the dataset is ready for accurate analysis. This involves handling mixed data types, extracting relevant information like the release year, and transforming the 'Genre' column into a more usable format.

### Key Questions Explored

The analysis seeks to answer several key questions:

* *What are the most common movie genres?*
* *Which genres receive the highest average votes from viewers?*
* *Which movies have the highest and lowest popularity scores, and what are their genres?*
* *Which year saw the highest number of movie releases in this dataset?*

### Analytical Approach

To address these questions, the project employs a variety of data analysis techniques:

* *Data Cleaning:* The Release_Date was converted to a more practical year format. Unnecessary columns like Overview, Original_Language, and Poster_Url were removed to streamline the dataset. The Vote_Average was categorized into meaningful groups such as 'popular', 'average', 'below_avg', and 'not_popular' to simplify the analysis of movie ratings. The Genre column, which initially contained multiple genres in a single string, was split and expanded so that each movie-genre combination is a separate entry, allowing for a more granular analysis.

* *Data Visualization:* The project leverages matplotlib and seaborn to create clear and informative visualizations. These include:
    * A *bar chart* illustrating the frequency of each movie genre.
    * A *bar chart* showing the distribution of vote averages.
    * A *histogram* to visualize the distribution of movie releases by year.

### Key Findings

The analysis of the data revealed several interesting insights:

* *Most Frequent Genre:* *Drama* is the most common genre in the dataset, appearing in over 14% of the movies analyzed.

* *Highest Voted Genres:* *Drama* also stands out as the genre with the highest number of popular votes, accounting for over 18.5% of movies rated as 'popular'.

* *Most and Least Popular Movies:*
    * The movie with the highest popularity score is *"Spider-Man: No Way Home,"* which falls under the *Action, Adventure, and Science Fiction* genres.
    * The movies with the lowest popularity scores are *"The United States vs. Billie Holiday"* (Music, Drama, History) and *"Threads"* (War, Drama, Science Fiction).

* *Peak Year for Film Production:* The year *2020* had the highest number of movies filmed, according to this dataset.

This project demonstrates a comprehensive approach to data analysis, from initial data cleaning to insightful conclusions. The findings provide a clear picture of the trends and patterns within the movie industry, offering valuable insights for both filmmakers and enthusiasts.
