# Game Recommendation System

### A machine learning-based Game Recommendation System designed to suggest video games based on content similarity and user preferences. The system leverages natural language processing and similarity algorithms to provide relevant game suggestions from a large dataset
---

# Features

- Data Handling: Uses **Pandas** and **NumPy** for data cleaning, transformation, and analysis of game metadata.
- Text Processing: Implements NLTK's **Snowball Stemmer** to normalize text data such as game tags and descriptions, improving matching consistency.
- Vectorization: Applies **CountVectorizer** to convert stemmed text into a matrix of token counts, enabling structured comparison of games.
- Employs **cosine similarity** and **K-Nearest Neighbors (KNN)** from **scikit-learn** to identify and rank similar games.
- Integrates **FuzzyWuzzy** for fuzzy string matching, allowing flexibility in user input and handling of partial or misspelled titles.
- Recommendation Logic: Combines text vectorization, fuzzy matching, and similarity scoring to generate a ranked list of recommended games based on a selected title or preference.
---
## Demo

Paste an game title (e.g., `Grand Theft Auto V`) and get similar recommendations instantly!

Example output:
![image]()
