# Music-Recommendation-System-
This repository contains a Music Recommendation System that suggests songs based on content similarity. The system applies natural language processing (NLP) and machine learning techniques to process track metadata and generate personalized playlists.

The preprocess.py script manages text cleaning, tokenization, and feature extraction using TF-IDF vectorization, followed by cosine similarity to measure relationships between songs. It prepares the dataset by removing stopwords, normalizing text, and combining relevant features like genres, keywords, and descriptions. Processed data and similarity matrices are stored for efficient use.

The api_utils.py module integrates with a music API to fetch additional details such as album art, lyrics, or previews, enhancing the user experience.

A Jupyter Notebook (Music_recommendation_system.ipynb) provides a hands-on demo of training, testing, and interacting with the system, making it simple to understand and extend.

This project is perfect for exploring recommendation engines, text preprocessing, and API integration in Python.
