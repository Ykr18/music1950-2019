# music1950-2019
Music data preprocessing, analysis and recommendation based on the available dataset

This project is a continuation of Project 1 in DATA 601, where we had to explore the dataset freely.
In this project I have attempted to get the accurate length of the tracks by scraping the web and appending the values in the dataframe at the appropriate rows.

Once we have the a factually correct dataset, I have used Kmeans clustering to assign each song to a cluster. The selected songs' clusters' proportions are the same as those of the recommended songs to ensure a overall smooth recommendation.

The hypothesis of this project is that a song is likeable for you because of the following factors- danceability, loudness, acousticness, instrumentalness, valence, energy and age

The code will suggest a few songs after you input your recommendations. Try them out, let us know if the hypothesis is true or not!
