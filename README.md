# SENTIMENT-ANALYSIS-ON-MOVIES-REVIEWS

## Data Acquisition and Preparation:
Import necessary libraries and dataset.
Conduct exploratory data analysis to understand data characteristics.
Preprocess text data by cleaning HTML tags, punctuation, and stop words.
Perform lemmatization to reduce words to their root form.
Handle missing values and duplicates.

## Feature Engineering:
Extract text features using TF-IDF vectorization to represent text as numerical data.
Create dense feature representations by generating word embeddings.
Combine TF-IDF and word embedding features for a hybrid approach.
Scale features for optimal model performance.

## Model Building and Evaluation:
Employ logistic regression as the base classification model.
Fine-tune logistic regression hyperparameters for optimal performance.
Create an ensemble model combining TF-IDF and embedding-based models to enhance predictive power.
