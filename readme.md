# Sentiment Analysis of Google Playstore Reviews

This project focuses on exploration of different sentiment analysis methods and classifying the sentiment of Google Playstore text reviews split into three categories (Positive, Neutral and Negative). Precisely, we test the Lexicon Based Approach, Bayesian Networks and k-NN models.

## Features

* <b>Data Preprocessing:</b> We preprocess the review data by removing unnecessary columns, handling missing values, and transforming the text data through techniques such as lowercasing, tokenization, removal of stopwords, and lemmatization.

* <b>Visualization:</b> We visualize the frequency vectors of comments after Principal Component Analysis (PCA) for both original and preprocessed data to understand the distribution of sentiment in the dataset. Additionally, we check the proportions of each data class.

* <b>Lexicon-based Approach:</b> This approach utilizes predefined lists of words with associated sentiment polarities to classify the sentiment of each review. We analyze different thresholds for determining sentiment polarity and evaluate the accuracy of the classification.

* <b>Bayesian Network Approach:</b> We employ a probabilistic graphical model to represent the relationships between words or features in text data and the sentiment expressed in the text. The model learns from the data and provides sentiment classification based on learned probabilities. Additionally, we split the data into training and testing sets and use Multinomial and Bernoulli Naive Bayes classifiers to classify sentiment. We evaluate the accuracy, recall, precision, and F1-score of the classifiers.

* <b>k-NN Approach:</b> We use the k-NN algorithm to classify sentiment based on the similarity of reviews in a feature space. We explore the impact of the number of nearest neighbors on classification accuracy. We recommend an optimal value for the number of neighbors based on computational complexity and performance.

## Usage

To replicate the analysis and classification results, follow the steps outlined in the notebook and ensure all necessary dependencies are installed including the nltk library data.

## Note

This project was developed as a part of the Machine Learning course.

## Contributors

* Kajetan Sulwiński (siemieniuk)
* Szymon Siemieniuk (ekohachi22)
* Mikołaj Marmurowicz (Mickeyo0o)