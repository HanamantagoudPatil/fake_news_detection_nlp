**Fake News Detection Using NLP**

This repository contains a comprehensive project for classifying news articles as fake or real. The project leverages various machine learning models and text processing techniques to achieve accurate classification results.

****Project Overview****

Data Collection: Collected a dataset of news articles labeled as fake or real. The dataset was preprocessed to prepare it for analysis.

****Data Preprocessing:****

Text Cleaning: Removed noise from the text data, including punctuation, stop words, and special characters.

Feature Extraction: Employed techniques such as TF-IDF vectorization to convert text data into numerical format suitable for modeling.

****Model Building:****

Random Forest: Implemented the Random Forest classifier, which demonstrated robust performance in distinguishing between fake and real news articles.

Additional Models: Explored other machine learning models, including Logistic Regression, SVM and Naive Bayes, for comparative analysis.

Model Evaluation: Evaluated model performance using metrics such as accuracy, precision, recall, and F1-score. Conducted cross-validation to ensure model reliability.

Deployment: The Random Forest model was deployed using Streamlit, providing a user-friendly interface for users to input news articles and receive classification results in real-time.

****Try the App****

You can try out the Fake News Classification App [here](https://fake-news-detection-hnp.streamlit.app/)
