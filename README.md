# Movie Rating Prediction
### The goal of this project is to build a model that predicts the rating of a movie based on various features such as genre, director, and actors. This involves analyzing historical movie data and developing a regression model to estimate the rating given to a movie by users or critics.

# Project Overview
### Data cleaning
### Data Analysis
### Data Preprocessing
### Feature Engineering
### Model Building
### Evaluation 

# Dataset
### Name: Title of the movie.
### Year: Release year of the movie.
### Duration: Duration of the movie.
### Genre: Genre(s) of the movie.
### Rating: Rating given to the movie.
### Votes: Number of votes received for the movie.
### Director: Director of the movie.
### Actor 1, Actor 2, Actor 3: Lead actors in the movie.

# Data Cleaning and Preprocessing
### Handling Missing Values
#### Filled rows by unknown with missing director,actors and genres
#### filled rows by mean with missing ratings and votes
#### filled rows by median with missing duration and remove rows with missing years
### Data Transformation
#### Votes: Convert vote counts from string to integer and remove commas.
#### Year: Extract the year from the format.
#### Duration: Remove 'min' from the duration.
### Feature Encoding
#### Convert categorical features like genre, director, and actors into numerical values using techniques like label encoding or one-hot encoding.

# Exploratory Data Analysis (EDA)
### Top 10 actors: combine all actor columns into a single series and then identify actors with more appearence.
### Top 10 Movies by Rating: Identify and analyze movies with the highest ratings.
### Top 10 Genres: identify genres with more appearence.
### Movies Released Over the Years: Study trends in the number of movies released each year.
### Actors by Average Rating: Investigate which actors have the highest average ratings.
### Directors by Average Rating: Investigate which directors have the highest average ratings.

# Feature Engineering
### Encoding Categorical Features: Convert categorical features like genres and directors into numerical values.
### Feature Transformation: Normalizing data using mnmaxscalar.

# Model Building
### Model Selection: Choose appropriate regression models such as Linear Regression, Random Forest Regressor and Gradient Boosting Regressor
### Training: Train the model using the prepared dataset.
### Evaluation: Assess the model's performance using evaluation metrics to ensure it accurately predicts movie ratings.

# Conclusion
### The Movie Rating Prediction project provides insights into how various factors such as genre, director, and actors influence movie ratings. By building and evaluating a regression model, we can estimate the ratings of movies based on historical data, helping in understanding rating trends and making informed decisions in the film industry.

