# Phase 1 Project

## Project Overview

This project analyzes Microsoft needs of setting up a movie studio. Microsoft sells computing devices, cloud systems and services, software, and other products to consumers and businesses and would like to venture into movie production. Exploratory Data Analysis will generate insights for Microsoft on What movies to produce.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. I will be exploring what types of films are currently doing the best at the box office and translating my findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### Data Understanding

For this project, I used the imdb.title.basics, imdb.title.ratings and bom.movie_gross datasets. This datasets contain information on movie genres, The ratings on each movie, The studios they were created, The number of Votes for each movie, domestic gross, foreign gross and the running minutes of the movies. My target variables are genres, Number of votes, Domestic Gross and the running minutes.

### Methods

This project uses Exploratory Data Analysis including finding correlation between variables and grouping by genres

### Results
Most studios produce Drama movies as seen in the frequency table below.

![download](https://user-images.githubusercontent.com/115534560/201157142-5574384f-f81e-4491-b17d-b646320b484d.png)

There is a positive correlation between the number of votes a movie has and  the domestic gross. Therefore an increase in the number of votes increases the domestic gross as shown in the scatter plot below

![download](https://user-images.githubusercontent.com/115534560/201157229-f15cfc84-c5c2-4a42-b92c-0df763ce7ebd.png)

### Conclusions
This analysis leads to three recommendations for the head of Microsoft

1) To produce Drama movies. Most movies from the data set are Drama. They are cheap to produce hence most studios prefer Drama to any other Genre. Genres such as Action and Thrillers may be expensive to produce because of their destructive nature.

2) You might consider producing Action, Adventure and Sci-Fi. This genre has high number of votes which is positively correlated to the domestic gross income.

3) To produce Documentaries. Documentaries are also many in the dataset, second from Drama. Due to the nature of Documentaries, their production is relatively cheaper hence Microsoft will not have to spend a lumpsum of money at once on a studio. You can start off with documentaries then gradually grow the studio.
