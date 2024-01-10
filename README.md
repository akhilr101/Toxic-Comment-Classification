# Toxic-Comment-Classification

Four supervised machine learning classifiers were developed and evaluated for their ability to predict whether a social media comment is toxic or not. These classifiers include Logistic Regression, Random Forest, Support Vector Machine with Naive Bayes Features, and LSTM Neural Network.

# Preprocessing
The first step was to preprocess the data from the Kaggle Toxic Wikipedia Comments dataset. This involved removing any identifying information such as IP addresses and removing null values.

# Feature Engineering
Next, feature engineering was performed on the preprocessed data to extract useful features that could be used to train ML classifiers. Some of the features extracted include comment length, capitalization percentage, number of profanities, number of exclamation points, number of question marks, and TF-IDF. TF-IDF is a common technique used in NLP to reflect the importance of a term in a large document corpus.

# Models
Several ML classifiers were trained on the preprocessed and engineered data to compare their performance on the task of toxic comment classification. The models used include:

Logistic Regression: A linear model that uses a logistic function to estimate the probability of a binary outcome.

Random Forest: An ensemble model that combines multiple decision trees to make predictions.

Support Vector Machine with Naive Bayes Features: A model that uses both SVM and Naive Bayes algorithms to classify text.

LSTM Neural Network: A deep learning model that uses recurrent neural networks to capture sequential dependencies in text.

# Results
