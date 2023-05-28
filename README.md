# BoxOffice_Analysis

## Link to Presentation
"https://docs.google.com/presentation/d/e/2PACX-1vTuaYlPur7Zr9cW1cK86EELTbqPOUglXbmTP8XFMqhcnXhHOWHFMmcUVT9km7OY7rSq31ZTtBKyJa3V/embed?start=false&loop=false&delayms=3000" 


## Introduction
Microsoft is a global leader in the technology sector. The company is known for its innovation and success in a wide range of digital services and products. 

The demand for film and television content demand has been on the rise.Among the chief drivers of this demand is the proliferation of smartphones and availability of streaming platforms to consume film and tv content via these devices. Streaming services such as Netflix, Amazon Prime and Hulu made a total of $25.2 billion in revenue in 2020. This shows a clear demand for this type of content. Other statistics also show the global box office revenue itself is projected to increase in the coming years.

Microsoft is well positioned to make a significant impact in the film industry given their extensive resources and wide range of technical expertise. However in an ever-competitive film industry, knowing which movies to produce that will capture audience interest is crucial. This project aims to assist Microsoft's new movie studio in making strategic decisions about which types of films to produce. By analyzing various aspects such as movie genres, budgets, and ratings, it aims to provide three insightful recommendations to the studio's executives, film producers, and creative team to help guide their movie production choices and strategies.


## Problem statement 
Microsoft has observed that all the big companies are creating original video content. The company would like to capitalize on this opportunity and have decided to create a new movie studio. However, they do not know much about creating movies. Using the data provided, this project explores what types of films are doing the best at the box office. The findings will be translated into actionable insights that will inform the head Microsoft's new studio decisons on what types of films to create.


### Stakeholder and Key Business Questions 
> 1. Which films are doing well and why? 
> 2. What attributes affect the success of a movie? 
> 3. How can Microsoft Studio's executives use this analysis to inform their new movie studio?


### Objectives
Our objective for this project is to clean, manipulate and analyse the data to create three visualizations through our analysis that can be translated to three recommendations. 

## Data Understanding 
The datasets used in this project come from reputable sources such as Box Office Mojo, IMDB, The Movie DB, and The Numbers, providing a comprehensive view of movie industry trends. These are all reliable databases where information is regularly updated and the websites routinely maintained.

>> 'bom_gross' obtained from Box Office Mojo, contains information about the title of the movies, studio that produced the movies, domestic and foreign gross.

>> 'imdb_ratings' and 'imdb_basics' were obtained from IMDB and contain information about the average ratings of the movies, the number of votes, the primary and original titles of the movies, the start year, the genres and the runtime minutes.

>> 'tn_movie_budgets' was obtained from The Numbers and contains information about: the worldwide gross, the domestic gross and the production budget of movies.

>> 'tmdb_movies' was obtained from The Movies and contains information about the release dates and popularity of movies .

Overall, the datasets include important information about film budgets, genres, ratings, gross earnings, and more. This data allows us to analyze various aspects related to the profitability and popularity of different types of films.

The number of records in the data frames vary from 3387 records to 146144 records. These data frames contain both integer and object data types. Two of the dataframes in use in this analysis are from the same source. Some data frames contain columns where large amounts of data are missing.

Some data are missing, and not all data are uniform across different sources, which might have an impact on our analysis. This means that we will not be able to merge data from different data frames as they are from different sources.


## Data Analysis 
### Methods

This project used pandas as the primary library for data manipulation, using many of its methods to load, clean and manipulate dataframes.

Other methods utilised for the analysis are:

>> Data cleaning methods such as splitting and exploding.

>> Data transformation methods such as the creation of new columns.

>> Desecrpitive statistics used to get a summary of the central tendency, dispersion and shape pf the distribution in the datasets.

>> Data visualization tools like matplotlib.pyplot to visualise our data and insights in order to understand the distribution of data and correlation between variables.


## Conclusions
From the visualisations as seen in the notebook and non technical presentation, it is possible to infer:
>> 1. Patrons preferred films with a runtime of 3 hours or longer and those that lasted an average of an hour. These films received a higher rating on average.

>> 2. Short films, documentaries and game shows are the most popular genres.

>> 3. The production budget is positively correlated with gross (both domestic and worldwide) for the movies. This means that a higher production budget is associated with higher gross returns.


## Recommendations 
Three recommendations for Microsoft's Head of Studio as the company opens a new movie studio are:

>> 1. Invest in Documentaries and Short films: These genres show the highest average ratings. Microsoft could consider creating content in these genres to attract viewership and positive reviews, which could lead to higher overall visibility and success.

>> 2. Consider longer runtimes for higher ratings: Films that are 3+ hours long and around 1 hour long tend to get higher ratings. Depending on the type of content Microsoft plans to produce, consider these lengths to attract viewership and positive reviews.

>> 3. Balance the Production Budget: There is a positive correlation between production budget and gross earnings (both domestic and worldwide). This suggests that investing more in production could potentially lead to higher earnings. A limitation to our findings is,  this correlation however  is not the strongest, implying that a high production budget does not guarantee high returns. Microsoft should balance their production budget, ensuring that they have enough budget for marketing and other post-production activities. This analysis could be improved by looking into more datasets that might give more insight into how production budgets and movie success could relate by relating other aspects of creating a film. 

