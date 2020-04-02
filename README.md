# Hackathon---Eurowatt
Sentiment analysis based on scraped tweets about the development of wind farms (in France)

Three Python notebooks for:
  1. Scrape Tweets: scraping tweets from twitter based on criteria (search query, date, location etc.) and saving as csv.
  2. Retrieve number of followers: based on user input list, retrieve the number of followers from the public accounts of the previous nb
  3. Sentiment Analysis: calculation of polarity for the tweets collected above. This nb inclused:
      - Transaltion: FR to EN
      - Text manipulation: remove unwanted characters, patterns, twitter handles
      - Tokenisation: remove stopwords, perform spell correction
      - Sentiment analysis: assign sentiment, calculate polarity, compound score
      
 Results are visualised in Tableau:
  - Dashboard with French municipalities: https://public.tableau.com/profile/jonathan.scheepers#!/vizhome/Municipality-SentimentGreenscore/Siteselection
  - Map with sentiment impact: https://public.tableau.com/profile/jonathan.scheepers#!/vizhome/SentimentAnalysis-WindFarms/Sentiment
