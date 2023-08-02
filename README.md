# Sentiment Analysis for Movie Reviews

This project performs sentiment analysis on movie reviews using VADER sentiment analyzer and machine learning models. The goal is to predict whether a review is positive, negative, or neutral based on the text.

## Data Collection
The dataset consists of movie reviews scraped from IMDb for five movies. Each review is labeled as positive, negative, or neutral.

## Data Preprocessing
The collected reviews are preprocessed by removing stop words, punctuation, and converting text to lowercase. Additionally, stemming and lemmatization techniques are applied to reduce words to their base forms.

## Sentiment Analysis Approaches
Two approaches are used for sentiment analysis:

### VADER Sentiment Analyzer: 
VADER is a rule-based approach that provides quick insights into sentiment analysis. It uses predefined lexicons to assign sentiment scores to words.
### Machine Learning Models: 
Support Vector Machine (SVM) and Decision Tree classifiers are implemented using TF-IDF vectorizer and count matrix for feature extraction.
Evaluation
The performance of the sentiment analysis models is evaluated using metrics such as accuracy, precision, recall, and F1-score. The results are compared for each approach.

## Findings
The results of the evaluations show that both VADER and machine learning models achieved varying levels of accuracy in sentiment prediction. VADER's rule-based approach provides quick insights but struggles with subtle nuances in language and context. On the other hand, the machine learning models heavily rely on training data, and limited dataset size can impact their performance.

## Conclusion
This project demonstrates the challenges and opportunities in sentiment prediction for movie reviews. While VADER provides quick insights, the machine learning models offer more flexibility and can potentially yield better results with a larger and more diverse training dataset

** For detailed evaluation, check the report **

