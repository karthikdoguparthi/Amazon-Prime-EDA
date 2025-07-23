# Amazon-Prime-EDA

Youtube: https://www.youtube.com/watch?v=pnpCrS8msN4

The goal of this project is to perform a comprehensive Exploratory Data Analysis on Amazon Prime using two datasets that includes detailed information about movies and shows available on the platform. The analysis aims to uncover insights about content trends, audience preferences, platform strategy, and factors influencing content performance.

The dataset combines Two CSV files and contains columns such as person_id, id, name, character, role, title, type, description, release_year, age_certification, runtime, genres, production_countries, seasons, imdb_id, imdb_score, imdb_votes, tmdb_popularity, and tmdb_score. After merging both datasets on the common id column, the combined dataframe was cleaned and transformed to make it suitable for analysis. This included handling missing values, parsing nested fields like genres and production countries, and filtering or converting data types where necessary.

The analysis starts with identifying the distribution of content types as Movie vs Show, frequency of genres, most common age certifications, and runtime distributions. Visualizations such as bar charts, pie charts, histograms, and word clouds help in summarizing the dataset composition. It was found that movies dominate the platform, and genres like Drama, Comedy, and Thriller are most watched. The most common age certifications are TV-13 and PG, suggesting a focus on mature audiences.

Line chart shows how the volume of content released has changed over time, with a noticeable increase in recent years. Box plots compare IMDb scores across genres and types, while scatter plots show how runtime relates to IMDb ratings. It was observed that shows tend to receive slightly higher average IMDb scores than movies within the same genre. Most content has a runtime clustered between 50 to 150 minutes, with longer durations generally associated with higher ratings.

A Heatmap was created to analyze IMDb score trends by genre across decades, showing how genres like Drama, Comedy and Thriller have gained higher audience ratings in recent decades. Correlation heatmaps and pair plots between numerical fields such as runtime, release_year and type helps in identifying weak or strong linear relationships, as well as outliers or clusters.

Key takeaways include identifying which genres are most highly rated, how audience preferences have shifted over time, and where Amazon Prime content is most viewed. These insights could help guide platform decisions such as which genres to invest in, what types of shows get better user engagement, and which markets might need more localized content.
