# Movie-Reccomendations

## Data Source
The dataset utilized in this project is the MovieLens 100K dataset, which is publicly available for research purposes. It comprises user ratings, movie information, and user demographics.
Note: the datasets used are provided in this repository as [Movie_Id_Titles](https://github.com/ann-o-maly/Movie-Reccomendations-System/blob/main/Movie_Id_Titles), [u.data](https://github.com/ann-o-maly/Movie-Reccomendations-System/blob/main/u.data) and [u.item](https://github.com/ann-o-maly/Movie-Reccomendations-System/blob/main/u.item).

## Language and Libraries Used
- Python: The primary programming language used for data processing and model implementation.
- pandas: For data manipulation and analysis.
- NumPy: To perform operations on arrays.
- scikit-learn: For implementing machine learning algorithms.
- matplotlib: For data visualization.

## Installation and Running Guide
This was done using Google colab so the only installation required are the datasets we will be using. 

## Features and Techniques
This project explores various recommendation system techniques, including memory-based collaborative filtering and model-based collaborative filtering. We preprocess the data, explore the dataset to understand the distribution of ratings and movies, and then implement different recommendation algorithms to suggest movies to users.
Memory-based models here are based on similarities between items or users, where we use cosine similarity and model-based CF is based on matrix factorization, where we use SVD to factorize the matrix. We must note that in a cold-start situation where there is very little data available on the items and users, these methods do not perform well unfortunately.
