# NLP-for-Stack-Overflow

## Summary 
The following project was part of a Kaggle competition between Master's Students of the University of Geneva. 
Link for the competition's description: www.kaggle.com/competitions/ml-unige-fall-2023-stackoverflow-classification/overview/description

The datasets used are available on the "CSV_Files.zip"

## Description of the NLP Project

Leveraging machine learning techniques to predict missing tags in Stack Overflow's posts.
This project focuses on Natural Language Processing (NLP), a specialized domain within Machine
Learning dedicated to comprehending, forecasting, and processing words, sentences, and the
intricacies of ”natural” language.
Our project aims to enhance the user experience on Stack Overflow, a programmer’s invaluable
resource, by leveraging machine learning techniques to predict missing tags in posts. Stack Overflow
has initiated the analysis of internal data spanning the past 15 years. Unfortunately, some posts
lack crucial data—specifically, the tag or subject of the post is absent.
Stack Overflow has provided a data set comprising
posts and their associated tags. As ML specialists, our primary challenge involves effectively
processing these text data using natural language processing (NLP) methodologies.
The project centers around the development of machine learning models capable of predicting
the diverse tags (categories) assigned to given posts. These posts, contributed by Stack Overflow
users, predominantly cover programming languages and comprise a blend of natural language and
code snippets in various programming languages.
The goal of the ML model is to be as accurate as possible in predicting the labels.

The document is divided as following
* Data Exploration and preliminary Analysis
  * Importation of required libraries.
  * Inspection of the dataset
  * Distribution of words
* Data preprocessing
  * Defining preprocess function
  * Split between training and test datasets
  * Tokenization
* Classification models
  * Random Forest Clasifier (RF)
  * Implementation of cross-validation for RF
  * Confusion Matrix for RF
  * Support vector classifier (SVC)
  * Cross validation with different kernels
  * Confusion Matrix for SVC models
* Tags Classification
  * Implementation of WordCloud to see the distribution of keywords for predefined tags
  * TF-IDF and Count Vectorizer Scores
* Prediction on final data
  * Saving the predictions in a CSV file for kaggle competition.
 
### Final conclusions
Overall, the model shows promising performance. However, there’s variability in performance across different classes,
indicating potential areas for improvement, especially for classes with lower precision, recall, and
F1-scores. Analyzing these metrics helps identify specific areas where the model struggles, providing
insights for potential model enhancements or targeted data improvements to boost performance,
especially for classes with lower scores.
