# Computational literacy final research project
In this project I analyse movie reviews to uncover the features that contribute to the success or failure of films within specific genres. I process and manipulate a dataset of IMDb movies which I obtained from Kaggle. I identify the highest and lowest-ranked genres and their top five best and worst movies based on average reviews. I locate the most popular reviews for each movie and analyse them using the appraisal framework and content analysis. My goal is to point out and analyse the key characteristics that make movies receive high or low ratings. After my analysis is complete, I tie my results into interdisciplinary knowledge and recommend further research.

## Files of the project
Here is a list of the files associated with this project.
- 'imdb_movies.csv' contains the tabular data of over 10 000 movies sourced from IMDB. It is a CSV file which can be obtained from kaggle.
- 'project.ipynb' contains the python code used in the project and it is a Jupyter Notebook file.
- 'Reviews.pdf' contains the viewer reviews that were extracted from the IMDB website and used for the analysis. The reviews are about the top five movies of the best genre and the worst five movies of the worst genre.
- 'Research project_detailed.pdf' contains the complete report of the project including detailed descriptions of the data processing and analysis as well as results and discussion.

## Research questions
1.	Which genres have the highest and lowest overall scores on IMDb?
2.	Which movies are the top five in the highest ranked genre and which movies are the last five in the lowest ranked genre?
3.	What makes the highest ranked movies of the best genre so good according to reviewers?
4.	What makes the lowest ranked movies of the worst genre so bad according to reviewers?

## Data
- The tabular data containing e.g. the genres and scores of the movies can be obtained from kaggle. It is titled IMDB movies dataset, and the link is https://www.kaggle.com/datasets/ashpalsingh1525/imdb-movies-dataset.
- The viewer review data can be found from the IMDB website from the pages corresponding to the movies analysed. The analysed reviews are the most popular ones.

## Data reproducing
- I filtered the CSV data from kaggle to contain only movies released in 2020 at the latest.
- I gave the genre label 'No Genre Assigned' to the movies that did not have any genre assigned in the CSV.
- Movies that belong to multiple genres have a string with unneccessary unicode characters ('\xa0') in the genre field -- I removed these '\xa0' strings from the data. Also, when a movie belonged to multiple genres, I counted its score individually toward each genre that it belongs to.

## Analysis of reviews
I conducted the analysis of reviews using the appraisal framework and content analysis methods to identify key features that contribute to the success or failure of movies. The appraisal framework focused on evaluating the emotional and evaluative language used in the reviews, categorizing terms into affect, judgment, and appreciation. I employed content analysis to categorize and quantify thematic elements mentioned in the reviews, such as plot, acting, direction, and special effects. These methods along with close reading provided key characteristics and patterns from the movie reviews. 
## Results
The main results revealed that highly-rated movies are praised for their artistic merit, strong emotional impact, skilled direction, and compelling themes, while poorly-rated movies are criticized for their poor writing and acting, lack of coherence, bad direction, and technical flaws. The dual-method approach of the appraisal framework and content analysis provided a comprehensive understanding of the factors that influence movie reception.
## Discussion and biases
Potential biases and challenges included the not complete selection of reviews from IMDb and inherent biases in the dataset. Additionally, I encountered data processing challenges such as handling missing values, genre classification, and identifying outliers. Future research could expand the analysis to include reviews from different platforms and cultural contexts, and integrate other disciplinary perspectives, such as psychology and media studies, to provide a more comprehensive understanding of the complex dynamics that influence the reception of films and their impact on audiences.
