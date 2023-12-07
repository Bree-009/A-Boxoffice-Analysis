# A Box Office Analysis
## Introduction
Watching movies has become increasingly popular in the fast pace of modern life. People watch movies to relax, learn life skills, learn a new language, get motivation, or even as background noise as they do something else. 
As of early 2022, Netflix, a popular streaming site, recorded  users watching over 400 million hours of content per week globally.

The box office refers to the degree of success of a film or play in terms of the number of people who go to watch it or the amount of money it makes. 
According to Medium; the recipe for creating a box office success is complex and multifaceted. It requires a combination of compelling storytelling, talented actors, stunning visuals, strategic marketing, cultural relevance, and above all else, an emotional connection with the audience.


Microsoft wants to venture into movie production but they lack expertise in filmmaking.
This project will involve analyzing data from different sources to figure out which movies are doing the best at the box office. Insights will then be derived from the analysis to provide more information to the head of Microsoft's studio.

## Problem Statement
After observing the success of other big companies in original video content creation, Microsoft wants to venture into movie production. They want to open a studio but they lack expertise in filmmaking. The task is to conduct an analysis of trends and successful genres doing well at the box office. The findings will then be translated into actionable insights and recommendations for the head of Microsoft's movie studio. These insights will be used to guide the decision-making process regarding the types of films Microsoft should focus on producing to maximize commercial success and audience engagement in the competitive movie industry.

## Main Objective
To provide actionable insights based on an analysis into the films dominating the box office.

## Specific Objectives
- Analyze datasets to find out which types of films are dominating the box office.
- Provide findings and recommendations from the analysis.
- Provide actionable insights that will help Microsoft in its video creation journey.

## NoteBook Structure
1. Data collection
2. Read data
3. Data wrangling
4. Exploratory Data Analysis
5. Conclusions 
6. Recommendations

## Data Understanding
The data used in this project was obtained from: [Box Office Mojo](https://www.boxofficemojo.com/),  [IMDB](https://www.imdb.com/),  [Rotten Tomatoes](https://www.rottentomatoes.com/), [TMDB](https://www.themoviedb.org/) and  [The Numbers](https://www.the-numbers.com/).

- The **Box Office Mojo Dataset** contains *5 columns and 3387 rows*. The columns are: 'title', 'studio', 'domestic_gross', 'foreign_gross', and 'year'. This Dataset is relevant as it shows which movies studios are making and the income they have earned from the movies.
- The **IMDB Dataset** contains *9 tables* each with its own columns. The tables include 'movie_basics' which has information like run times and titles of movies and 'movie_ratings' which has average ratings and number of votes a movie got.
- The **Rotten Tomatoes Dataset** contains *1560 rows and 12 columns*. The columns are: 'id', 'synopsis', 'rating', 'genre', 'director', 'writer','theater_date', 'dvd_date', 'currency', 'box_office', 'runtime', 'studio'. This dataset provides insight into movie genres, their ratings, the writers, and even air dates.
- The **TMDB Dataset** contains *26517 rows and 10 columns*. The columns are:'genre_ids', 'id', 'original_language', 'original_title', 'popularity', 'release_date', 'title', 'vote_average', 'vote_count'. This dataset provides extra information about original languages, popularity, and titles for movies.
- The Dataset from **The Numbers** contains *5782 rows and 6 columns*. The columns are: 'id', 'release_date', 'movie', 'production_budget', 'domestic_gross', and 'worldwide_gross'. This dataset is relevant as it shows movie, how much the budget for production was, and how much income they grossed worldwide.

  ## Methodology

  ## Conclusions

- Majority of movies fall within the duration range of 80 to 150 minutes. This duration seems to strike an optimal balance, allowing for a comprehensive narrative while maintaining audience engagement throughout the film.

- A higher production budget doesn't inherently guarantee a higher gross income, nor does a lower budget guarantee a lower gross income. 

- Movies rated as NR and R tend to occur most frequently, suggesting a notable presence of films falling within these rating categories.

- Languages such as Mandarin Chinese, Yue Chinese, Persian, Serbian, and Swedish appear prominently in the highest-rated movies. 

- Drama, Documentary, and Comedy are the most prevalent genres among the movies analyzed.

  ## Recommendations

- Movie Durations - The observation that most movies fall within the 80 to 150-minute range suggests that this duration strikes an optimal balance, allowing for a comprehensive narrative while maintaining audience engagement throughout the film. Consider making movies that fall within this range.

- A higher production budget doesn't inherently guarantee a higher gross income, nor does a lower budget guarantee a lower gross income. The success of a movie depends on many other elements. While an adequate budget is important, the ultimate performance of a film is influenced by various factors such as production quality, cast, and set design. Focus on factors beyond budget, such as script quality, cast talent, effective marketing, and audience targeting, to optimize revenue generation.

- Noting that NR (Not Rated) and R-rated movies have the highest frequencies implies a bigger market for mature and non-rated content. Tailor movie creation to target these audience segments.

- Identifying Mandarin Chinese, Yue Chinese, Persian, Serbian, and Swedish as languages associated with highly-rated movies suggests potential markets where films can find success. Consider diversifying language options to reach a broader audience.

- Popular Movie Genres: The insight that Drama, Documentary, and Comedy are the most made genres highlights their popularity among filmmakers and audiences. Explore these genres or combinations of them to create unique films. 
