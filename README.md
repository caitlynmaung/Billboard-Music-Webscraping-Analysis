1. Introduction

   Our goal was to analyze trends in music over the past decade (2010-2023) in terms of genre, sentiment, and audio features. In a team of 3, I was responsible for leading the webscraping process from the Billboard Hot 100 charts to access the top 10 songs for each month of 2010-2023. I also worked on performing sentiment analysis for each song based on their lyrics from the Genius website and plotted the results. My other team members worked on scraping song genres using the iTunes Search API, as well as scraping audio features from a third-party website called SongData.io, and plotting the results.

2. Methods
   We used libraries such as BeautifulSoup (to parse HTML content during webscraping), matplotlib (for plotting), datetime (for converting indices to date and time), and pandas (for data analysis and manipulation) throughout our analysis.

3. Conclusion
   We found that genres like Pop and Hip-Hop/Rap remained consistently popular across the decade while some years showed a rise in genres like Afrobeats. There was also a stable trend in positive sentiment songs, mostly due to the Pop genre having more upbeat songs. We also found correlations between audio features like danceability and energy and observed increasing acousticness and decreasing energy in songs over the past decade.
