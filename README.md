# Spotify Interpretive and Predictive Project
**Authors:** Joe Swing, Lorin Helfenstein, Colette Crowder

## Overview
The goal of this project is to find out what factors make songs popular and lead to reaching the 100 position charts. From there, we created models that can predict whether or not a particular song will be on the 100 position charts.

## Business Problem
Our hypothetical business problem is: What kind of song should an up-and-coming musical artist create? The artist that has approached our company wants to be as successful as possible and produce a song that makes it onto the charts. We have been tasked with discovering what factors lead to a song's popularity. Our findings will allow us to make reccomendations about what the artist's next song should be like.

## Data
We worked with two separate datasets, both containing data about various songs. There was a lot of overlap between the two, but one dataset has information about whether or not a song was on the 100 position charts and the other dataset has information about each song's popularity. These two variables were our target variables. We worked with many predictor variables, including loudness, danceability, and speechiness. We ran separate analyses on the two datasets. 

We got our datasets from Kaggle, where others collected the data by webscraping from billboard and shazam and using Spotify Web API.

## Methods
Our process started with organizing our data by dropping irrelevant columns, creating new ones, sorting by specific values, and merging dataframes. While modeling our data, we used descriptive statistics to create helpful visuals that displayed our findings. Overall, our descriptive analysis is absolutely essential for anyone who wants to succeed in the movie industry.

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

## Conclusions
We recommend that Microsoft uses Buena Vistas studios or models their own studio after BV practices and creates an adventure movie with an NR rating. They should also hire Jean Negulseso. The run time of the movie should be between 100 minutes and 131 minutes. Microsoft should not put time and money into securing any particular release month.

## Next Steps
This project did not explore all possible avenues of increasing movie profitability. In the future, analyses could be performed regarding the actors who Microsoft should hire, what kind of storylines are received best by audiences, and what aspects of a movie trailer cause people to develop interest in seeing a movie. Additionally, it could benefit Microsoft to learn about the state of the film industry after COVID-19, which shut down theatres for a long period of time and may have impacted audience interest in ways that are not known yet.

## For More Information
Please review our full analysis in [our Jupyter Notebook](./Final/Notebook.ipynb) or our [presentation](./microsoftmovieanalysispowerpoint.pdf).

For any additional questions, please contact **Joe Swing at jcswing@bsc.edu, Lorin Helfenstein at le, or Colette Crowder at crcrowde@bsc.edu**

## Repository Structure

```
├── data                                  <- data files used for analyses
├── images                                <- visualizations created
├── Final Notebook.ipynb                  <- code written for project with explanation
├── microsoftmovieanalysispowerpoint.pdf  <- PDF version of powerpoint
└── README.md                             <- overview of project
```