# Sentiment-Analysis-with-Python-Project-Movie-Review-Sentiment-Analysis-
creating own sentiment analysis project in Python, targeted towards a specific sector of your choice. Your project should be implemented in a Jupyter notebook, showcasing the entire process from data acquisition to analysis and visualization.

Step 1: Data Acquisition
In this step, we aimed to gather movie reviews from IMDb using the IMDbPY API. IMDbPY is a Python package that allows us to interact with the IMDb database, fetching movie details and reviews. We initiated an IMDb object, searched for a movie by its title (for example, 'The Dark Knight'), and obtained its unique movie ID. Then, we retrieved reviews for that movie using its ID.

Step 2: Data Processing and Cleaning
Data processing and cleaning are crucial before performing sentiment analysis. We focused on preparing the raw text data obtained from IMDb reviews for sentiment analysis. The cleaning process involved converting all text to lowercase and removing punctuation marks using Python's string manipulation methods. This cleaning step helps standardize the text data, making it more consistent for analysis.

Step 3: Sentiment Analysis Implementation
For sentiment analysis, we utilized TextBlob, a Python library for processing textual data. TextBlob simplifies sentiment analysis by offering an intuitive interface to analyze sentiments in text. We defined a function to analyze the sentiment of each review. The sentiment analysis process involves creating a TextBlob object for each cleaned review and extracting the polarity score, which indicates the sentiment (positive, negative, or neutral) of the text.

Step 4: Results Visualization
After obtaining sentiment scores for each review, visualization aids in understanding the distribution of sentiments across the dataset. We used Matplotlib, a popular data visualization library in Python, to create a histogram. This histogram displayed the distribution of sentiment scores, dividing the scores into bins and showcasing the frequency of different sentiment polarity scores.

The histogram visualizes the spread of sentiment in the movie reviews, giving an overview of how positive, negative, or neutral the audience's opinions might be.
