# Sentiment Analysis with IMDb Reviews
This project is a Python-based sentiment analysis tool that uses the NLTK library and a dataset of IMDb movie reviews from Kaggle to determine the overall sentiment of a given text as either positive or negative.

## Getting Started
To run this project, you will need to have Python installed on your machine. You will also need to install the following libraries:

- pandas
- nltk
- scikit-learn

You can install these libraries using pip by running the following command:

`pip install pandas nltk scikit-learn`
## Data
The data used in this project comes from the IMDb movie reviews dataset on Kaggle. This dataset contains movie reviews labeled as either positive or negative.

## Preprocessing
The text data is preprocessed by removing stopwords, lemmatizing words, and converting all text to lowercase. This is done using the preprocess_text function in the code.

## Feature Extraction
Features are extracted from the preprocessed text using the TF-IDF (Term Frequency-Inverse Document Frequency) method. This is done using the TfidfVectorizer class from scikit-learn.

## Model Training and Evaluation
Three different models are trained and evaluated on the data: Naive Bayes, Logistic Regression, and Support Vector Machine (SVM). The models are trained on the training data and evaluated on the test data. The accuracy of each model is printed to the console.
