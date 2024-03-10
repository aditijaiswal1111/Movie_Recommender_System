# Movie Data Analysis

## Introduction
This project involves analyzing movie data obtained from the TMDB (The Movie Database) API. The dataset includes information about movies, including their cast, crew, keywords, genres, overview, and title.

## Data Preprocessing
1. Merging Dataframes: The project involves merging two datasets - `tmdb_5000_credits.csv` and `tmdb_5000_movies.csv`.
2. Removing Unwanted Columns: Some columns such as budget, homepage, and original language were removed as they were not relevant to the analysis.
3. Handling Missing Data: Missing values were identified and handled appropriately.
4. Data Conversion: Certain columns containing JSON-like strings were converted into lists for easier analysis.

## Data Analysis
1. Genres: The genres column was processed to extract genre information for each movie.
2. Keywords: Similar to genres, the keywords column was processed to extract keyword information.
3. Cast: The top three cast members for each movie were extracted from the cast column.
4. Crew: The director for each movie was extracted from the crew column.
5. Overview: The overview column was processed to tokenize the text for further analysis.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Getting Started
1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook `movie_data_analysis.ipynb` to see the data preprocessing and analysis steps.

## Conclusion
This project provides insights into movie data, including genre trends, popular keywords, and cast members. Further analysis could involve sentiment analysis of movie overviews or predicting movie success based on various features.

