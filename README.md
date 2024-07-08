# recommender-project

Author : Jean-Michel Naud SCIA 2025

Data Collection and Preprocessing:

    Download and merge MovieLens and IMDb datasets to include movie ratings, genres, and metadata.
    Extract the year from movie titles and standardize the movie titles.
    Merge datasets and remove duplicates.

Feature Engineering:

    Handle missing values and split genres into individual columns.
    Generate movie features and normalize them.
    Aggregate user features and normalize them.

Model Development:

    Implement a neural network model to predict movie ratings.
    Use the L2 normalization layer for better model performance.
    Train the model and evaluate its performance using RMSE.

Recommendation Algorithm:

    Develop an algorithm to suggest movies based on two liked movies.
    Predict ratings for all movies and recommend the top-rated movies.

Evaluation:

    Split the data into training and testing sets.
    Evaluate the model using RMSE to ensure it performs well.