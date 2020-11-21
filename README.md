# Movie-Analysis
Author: [JingYun (Jonna) Wang](/jingyunwang24@gmail.com)

<img src="images/movie_analysis.jpg">

## Overview
This project analyzes the movie industry on multiple large data sets. These data sets include different types of movie information. Descriptive analysis helps define "successful movies" in financial terms and what contributes to "successful movies". Stakeholders can use this analysis to determine the movie genre, directors, writers, movie length, and release month. 

## Business Problem
Microsoft's subsidairy sees an opportunity and has decided to create a movie studio to make original video content. Using this movie analysis, stakeholders can determine movie structure and produce successful movie by hiring top directors and writers.

## Data
The [IMDb](/https://datasets.imdbws.com/) website is the most popular movie website which combines many aspects of movie information(e.g. genres, title, cast). Each movie has a unique identifier (<b>tconst</b>) and each related person also has a unique name identifier (<b>nconst</b>). [The Numbers](/https://www.the-numbers.com/movie/budgets/all) website provides detailed movie financial analysis which tracks box office revenue in a systematic, algorithmic way.

## Methods
This project uses descriptive analysis which provides the basic feature of data and helps determine the resource needed.

## Results
To produce a successful movie, stakeholders need to determine the movie genres, people who will be hired, the movie length and the best release month. 

The top 5 genres among successful movie dataframe are: Drama, Comedy, Action, Adventure, and Thriller. 
<img src="images/Genre Distribution.png">

Some genres have relative high budget compared to others. <br>
Combination of multiple genres can based on budget can be a good choice.
<img src="images/Average Budget by Genre.png">

There are 6 top directors and 8 top writers. Some of them have 100% successful rate while some of them have several unsuccessful movies. Both successful and unsuccessful experience are important. It would depend on stakeholders who prefer more on succesful rate or number of experience.
<img src="images/Top Directors and Top Writers.png">

Both November and December has the highest release of successful movies. 
<img src="images/Release Month Order.png">

The optimal movie length is between 97 and 121 minutes.
<img src="images/Movie Length.png">

## Conclusions
Among filtrated 1431 movies between 2010 and 2020, there are 740 movies considered as successful movies from perspective of returns. These successful movies analysis leads to 4 recommendations. 
* <b>Movie Genre</b> - The top 5 genres are Drama, Comedy, Action, Adventure, and Thriller. Additional analysis was provided to find the average budget for each of the genre. Usually, a succesful movie has more than one genre. Stakeholders can choose their desired combination genres based on the budget.

* <b>Directors and Writers</b> - There are 6 top directors and 8 top writers. Some top directors/top writers have perfect successful rate while some not. Both successful and unsuccessful experience are important. It would depend on stakeholders who prefer more on succesful rate or number of experience.

* <b>Release Month</b> - November and December are the best months for releasing successful movies. 

* <b>Movie Length</b> - The optimal movie length for a succeesful movie is between 97 and 121 minutes.

## Next Steps:
Because there is a limit amount of time and this is phase 1 project, I think further analysis can yield additional insight:

* <b>Prediction Analysis</b> - Prediction on how much gross can be earned based on different budget.

* <b>Datasets with Age groups</b> - The provided datasets did not cover age range. With the age provided, further descriptive analysis can be made on movie popularity for targeting towards specific age groups.

* <b>Movie Trailer</b> - A better movie trailers can attract more customers earlier. Select length and releasing date of movie trailers are also important factors of successful movies.

## For More Information
See the full analysis in the jupyter notebook .<br>
For additional information please contact, JingYun (Jonna) Wang at jingyunwang24@gmail.com