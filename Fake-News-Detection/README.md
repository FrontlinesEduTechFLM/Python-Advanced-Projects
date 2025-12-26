Fake News Detection using Machine Learning


In an era where misinformation spreads rapidly, detecting fake news is crucial to ensure the integrity of information. This project aims to develop a machine learning model that can classify news articles as "real" or "fake" based on their content. The system leverages natural language processing (NLP) and supervised learning techniques to detect patterns and characteristics common in fabricated news.


Key Features
Text Processing & Feature Extraction: Utilizes NLP techniques such as tokenization, stemming, lemmatization, and TF-IDF (Term Frequency-Inverse Document Frequency) to process and transform raw text data into meaningful features.


Machine Learning Algorithms: Implements a range of supervised learning algorithms, including:


Logistic Regression


Naive Bayes


Support Vector Machines (SVM)


Random Forests


Each algorithm is evaluated based on metrics like accuracy, precision, recall, and F1 score to determine the most effective approach for this classification task.



Model Training & Evaluation: Trains the model on a labeled dataset of real and fake news articles, followed by cross-validation to ensure robust performance and avoid overfitting. Hyperparameter tuning is applied to optimize the models further.



User-Friendly Interface: Provides a simple interface where users can input a news headline or article, and the model will return a prediction indicating whether the news is likely to be real or fake.



Datasets & Tools


Dataset: Uses a public dataset containing labeled real and fake news articles for training and testing the model.


Libraries & Tools: Python, scikit-learn, NLTK (Natural Language Toolkit), and Pandas for data preprocessing, model building, and evaluation.


Objectives


To detect fake news with high accuracy, reducing the spread of misinformation.

DataSet Links:

Fake CSV File :

https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets

True CSV File :

https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets


To enhance user awareness by providing insights into the reliability of online news sources.


To experiment with multiple ML models and NLP techniques, comparing their effectiveness in text-based classification.
