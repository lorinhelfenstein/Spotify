# Spotify Interpretive and Predictive Project
**Authors:** Joe Swing, Lorin Helfenstein, Colette Crowder

## Overview
The goal of this project is to find out what factors make songs popular and lead to reaching the 100 position charts. To figure this out, we created models that can predict whether or not a particular song will be a success.

## Business Problem
Our hypothetical business problem is: What kind of song should an up-and-coming musical artist create? The artist that has approached our company wants to be as successful as possible and produce a song that makes it onto the charts. We have been tasked with discovering what factors lead to a song's popularity. Our findings will allow us to make reccomendations about what the artist's next song should be like.

## Data
We worked with two separate datasets, both containing data about various songs. There was a lot of overlap between the two, but one dataset has information about whether or not a song was on the 100 position charts and the other dataset has information about each song's popularity. These two variables were our target variables. We worked with many predictor variables, including loudness, danceability, and speechiness.

We got our datasets from Kaggle, where others collected data by webscraping from billboard and shazam and using Spotify Web API. We also gathered data about songs created in 2021 by using the Spotify Web API for ourselves.

## Methods
In this project, we made and used multiple different models including:
Neural Networks
Decision Tree
Bagged Tree
Random Forrest
XGBoost
Grid Searching
Clustering

## Results

This visualization shows which genre of movie Microsoft should make based on which genre has the highest worldwide gross.

![graph1](./images/grouped_barplot_Seaborn_barplot_Python_corrected.png)

This is a visual of how Rotten Tomatoes user-generated ratings vary according to different MPAA ratings of adventure movies.

![graph2](./images/Rotten_tomatose_Ratings.png)

This graph shows the most profitable directors for adventure movies. We conclude that Jean Negulesco is by far the best choice.

![graph3](./images/Directors_and_Profit_for_Adventure_Movies.png)

Buena Vistas Studios ("BV") is responsible 65% of the top 20 grossing movies. If Microsoft is interested in using another studio to make their film, they should contact Buena Vistas.

![graph4](./images/top20_barplot_Seaborn_barplot_Python.png)

This is a comparison of runtime to revenue that reveals there is no true monetary value for creating a movie with a runtime outside of the shaded area.

![graph5](./images/Runtime_Comparison_line_added.png)

This graph shows the average rating of movies according to month of release. Because there is no significant difference between each month, we conclude release month doesn't really matter.

![graph6](./images/Month_and_Rating.png)

## Next Steps
If we had more time, we would have continued to work on the Spotify API and gotten the release dates for the songs to filter them and only use those songs from later than 2010. 

## For More Information
Please review our full analysis in [our Jupyter Notebook](./Final/Notebook.ipynb) or our [presentation](./microsoftmovieanalysispowerpoint.pdf).

For any additional questions, please contact **Joe Swing at jcswing@bsc.edu, Lorin Helfenstein at lehelfen@bsc.edu, or Colette Crowder at crcrowde@bsc.edu**

## Repository Structure

```
├── data                                  <- data files used for analyses
├── images                                <- visualizations created
├── Final Notebook.ipynb                  <- code written for project with explanation
├── README.md                             <- PDF version of powerpoint
└── Spotify.pdf                           <- overview of project
```