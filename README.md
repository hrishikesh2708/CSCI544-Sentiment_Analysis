# CSCI544-Sentiment_Analysis
This project delves into sentiment analysis by classifying text from Amazon product reviews. It aims to understand customer behavior by analyzing reviews, survey responses, and social media content. The process involves preparing datasets, cleaning data, preprocessing text, extracting features, and training models with various machine learning algorithms. The goal is to effectively identify positive and negative sentiments in the reviews.

### Dataset Preparation
- Utilize the Amazon reviews dataset for kitchen products.
- Focus on 'Reviews' and 'Ratings' fields, creating binary labels for sentiment analysis.

### Data Cleaning
- Convert reviews to lowercase, remove HTML, URLs, non-alphabetical characters, and extra spaces.
- Perform contractions (e.g., won’t → will not).

### Preprocessing
- Remove stop words and perform lemmatization using the NLTK package.

### Feature Extraction
- Extract TF-IDF features from the cleaned and preprocessed data.

### Model Training and Evaluation
- Train Perceptron, SVM, Logistic Regression, and Multinomial Naive Bayes models.
- Evaluate models based on accuracy, precision, recall, and F1-score.
"""
