# Data-Analysis-of-Spotify
Spotify Data Analysis: Key Insights
1. Presentation Overview and Data Context
The presentation is titled 

Spotify Data Analysis.

It was prepared by 

Sayan Hassan , GCECTB-R24-3030, CSE [3rd Sem], dated 

October 5, 2025.

The analysis focuses on predicting and explaining 

Popularity (Score 0-100) as the target variable.

Key features analyzed include 

Intensity (Energy & Loudness), Mood & Rhythm (Danceability & Valence), and Production Style (Acousticness & Instrumentalness).



2. Characteristics of "Hit" Songs (Popularity Analysis)

Elite Barrier: A track needs a Popularity score of at least 71 to be considered among the top 1% most successful tracks.



High Inequality: The dataset shows a massive skew in popularity, with the minimum popularity falling near-zero after 1976 and staying there for over 50 years, confirming that few mega-hits dominate while most songs remain obscure.


Popularity Share: The Top 1% accounts for 4.75% of total popularity, while the Top 10% accounts for 35.81%.


3. Track Feature Correlation with Popularity
Primary Drivers (Positive Correlation):


Energy (r=0.16) is the strongest linear positive predictor; intense, upbeat tracks are slightly more likely to be popular.


High Danceability (Concentrated in the 0.50 to 0.90 range) is a necessary ingredient for achieving high popularity (above 40).


High Energy (above 0.25) is also strongly correlated with maximum popularity; below 0.25, a score above 60 is nearly impossible.

Primary Barriers (Negative Correlation):


Instrumentalness (r=−0.15) is a strong negative factor; vocals are suggested as a necessary component to reach the elite level of success.



Duration must be short; the majority of popular tracks are tightly clustered under 6 minutes, and tracks longer than 10 minutes almost never exceed a popularity score of 25.


Liveness (Live Recordings) shows a preference for polished studio recordings (low liveness score below 0.30) for achieving maximum popularity.

Neutral Factors:


Acousticness shows no clear correlation with high popularity, suggesting both acoustic and digital tracks can be hits.


Valence (Mood, r=0.01) is also largely neutral, meaning hits can be happy or sad.

4. Language and Time-Series Trends
Language Volume & Dominance:


English is the primary language, representing 47.5% of the tracks in the dataset and showing an explosive rise in releases from ~900 (2019) to 3,300+ songs (2025).






Tamil (25.6%) and Hindi (11.7%) together show a significant South Asian presence (37.3%).




Korean music volumes surged around 2015, reflecting the global K-Pop boom (14.0% share).



Language Feature Profiles (Modern):


Korean music consistently has the highest median Energy (approx 0.8) and is significantly less acoustic (median near 0.0), reinforcing its bias toward upbeat, electronically produced sound.




Tamil tracks exhibit the highest median Valence (approx 0.7), suggesting a stronger tendency toward positive/cheerful moods.


Temporal Shifts:

There is a 

universal trend of decreasing acousticness over time across nearly all languages, indicating a shift toward digital production.



English music from the 70s, 80s, and 90s shows the 

highest historical popularity, but for the most recent decade (2020s), Korean music shows the highest average popularity.

5. Artist and Collaboration Insights

Collaboration: On average, Solo tracks are more popular (approx 17.8) than Collaboration tracks (approx 13.8) in this dataset, contradicting the common industry assumption.

Top Artists:


Taylor Swift dominates the metric for Most Songs in Top 10% Popularity with over 330+ songs.


The top artists by number of albums include 

Justin Bieber and Maroon 5 (550+ albums).


The longest singing careers belong to artists like 

Billy Joel and Alan Silvestri (~53 years).



One-Hit Wonders: Hindi top 10 one-hit wonders are heavily tied to film music (9 of top 10 from films), featuring artists like Arijit Singh frequently.
