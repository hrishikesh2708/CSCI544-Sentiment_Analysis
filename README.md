# CSCI544-Sentiment_Analysis

This project extends sentiment analysis to a more comprehensive study of Amazon product reviews, aiming to decipher customer sentiments. It encapsulates the entire pipeline from dataset preparation through model evaluation, leveraging both classical machine learning techniques and advanced neural network models. The ultimate objective is to proficiently classify reviews into positive, negative, and neutral sentiments, thereby offering valuable insights into customer preferences and behaviors.

### Dataset Preparation
- Derived from the Amazon reviews dataset, with a focus on kitchen products.
- Simplified into 'Reviews' and 'Ratings', with ratings transformed into binary and ternary labels for detailed sentiment analysis.

### Data Cleaning
- Standardized review texts by converting to lowercase, purging HTML tags, URLs, and non-alphabetic symbols, and rectifying spacing issues.
- Expanded contractions for consistency (e.g., "won’t" → "will not").

### Preprocessing
- Enhanced text clarity by excising stopwords and applying lemmatization, courtesy of the NLTK package.

### Feature Extraction
- Employed TF-IDF to distill meaningful features from the processed text data.
- Introduced Word2Vec embeddings to encapsulate semantic relationships, employing both custom-trained and pre-trained models.

### Model Training and Evaluation
- Deployed an array of models including Perceptron, SVM, Logistic Regression, Multinomial Naive Bayes, a Multi-layer Perceptron (MLP), and a Convolutional Neural Network (CNN).
- Assessed models using a comprehensive suite of metrics such as accuracy, precision, recall, and F1-score, ensuring a thorough evaluation of each model's capability to discern sentiments.

### Deep Learning Integration
- Integrated MLP and CNN models to explore the potency of neural networks in understanding complex text patterns, demonstrating significant advancements in sentiment classification accuracy.

### Insights and Conclusions
- Conducted in-depth analyses comparing the efficacy of various feature types (TF-IDF vs. Word2Vec) and model architectures, revealing the nuanced advantages of neural network approaches in sentiment analysis tasks.

This project not only solidified foundational sentiment analysis concepts but also ventured into the realms of deep learning, showcasing the symbiotic relationship between traditional NLP techniques and modern neural network models in extracting nuanced insights from textual data.
