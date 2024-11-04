# Spotify Data Analysis I

## Spotify Data Analysis using postgresql:
Using the provided attributes in the spotify dataset, this analysis was carried out targeting primarily on the following problem statements mentioned below: 

1. Retrieve the names of all tracks that have more than 1 billion streams.
2. List all albums along with their respective artists.
3. Get the total number of comments for tracks where licensed = TRUE.
4. Find all tracks that belong to the album type single.
5. Count the total number of tracks by each artist.
6. Calculate the average danceability of tracks in each album.
7. Find the top 5 tracks with the highest energy values.
8. List all tracks along with their views and likes where official_video = TRUE.
9. each album, calculate the total views of all associated tracks.
10. Retrieve the track names that have been streamed on Spotify more than YouTube.
11. Find the top 3 most-viewed tracks for each artist using window functions.
12. Write a query to find tracks where the liveness score is above the average.
13. Use a WITH clause to calculate the difference between the highest and lowest energy values for tracks in each album.
14. Find tracks where the energy-to-liveness ratio is greater than 1.2.
15. Calculate the cumulative sum of likes for tracks ordered by the number of views, using window functions.


## Query Optimization
During the course of this analysis, I leveraged indexing by adding indexes on frequent queries and used Explain Analyze to review and improve query performance.

# Spotify Data Analysis II

## Spotify Data Analysis Using PowerBi:
I leveraged Power BI to develop an interactive dashboard that uncovers our listening habits, most-streamed artists, genres, etc. The report analyzes the evolution of music focusing on key audio features and their impact on popularity, using a dataset comprising track metadata and audio features from Spotify.

📊Data Exploration:

Data Cleaning: I employed Power Query to:
- Remove outliers and address null values.
- Select relevant rows and audio features such as danceability and energy.
- Correct and reassign appropriate data types.

Furthermore, to monitor changes over time, I created a new “Calendar” table using DAX expressions.

Key Takeaways:
1. This dataset spans between 1930-2023.
2. The dashboard highlights daily and monthly listening patterns. 
3. Notably, January recorded the highest number of tracks and streams, with 127 tracks and over 734 million streams respectively. The data also indicates a variation in trends, with some months showing a lower number of tracks but higher streaming figures and vice versa.
4. 2022 recorded the highest number of streams with over 116 billion streams in the year.

## Dasboard

![Spotify](https://github.com/user-attachments/assets/aedd33b1-cbcb-4527-b2be-baffb810b35b)

This is an interactive dashboard and will love to have you access it. 
Link to interactive viz: [PowerBi](https://app.powerbi.com/reportEmbed?reportId=b6fc4c0d-3d50-418b-9096-108d7df4a84e&autoAuth=true&ctid=70cfb77d-317e-4eae-9a49-4e2ad1c1b93b)


