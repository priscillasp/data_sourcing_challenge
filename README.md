# Data Sourcing Challenge - Movie Recommendation System Data Preparation
## Overview
This project entails the preparation and merging of movie data extracted from The New York Times and The Movie Database (TMDb) APIs. The data collected supports the development of a movie recommendation system, in this case, the output csv was filtered for movie reviews with "love" in the headline.

## APIs Used
- The New York Times Article Search API: Used for fetching movie reviews.
- The Movie Database (TMDb) API: Used for obtaining detailed information about movies, such as genres, languages, and production countries.

## Data Collection and Processing
New York Times API:
- Movie reviews were fetched using specific filters for section names and material types, focusing on movie-related content. The query was filtered for movie reviews with "love" in the headline and searching for "Movies" and "Review". 
- Data such as headlines, publication dates, and review snippets were extracted.
The Movie Database (TMDb) API:
- Used movie titles obtained from NYT data to search for corresponding movie IDs in TMDb.
- Retrieved detailed data for each movie, including genres, languages, and production country details.

## Data Merging:
Merged data from both APIs based on movie titles to create a comprehensive dataset.
Cleaned and formatted the merged data to ensure consistency and readability.

## Final Output
nyt_tmdb_data.csv: Final merged dataset ready for use in the recommendation system, available in the data/ directory.
