About the Project
The Fake News Detection System uses Natural Language Processing (NLP) and Machine Learning (ML) techniques to identify fake news articles. It analyzes the content of news articles and predicts whether they are real or fake. The system uses traditional machine learning algorithms like Logistic Regression and Random Forest to classify news articles with high accuracy.

This project is built using Streamlit, a Python framework for building interactive applications, to create an easy-to-use web-based interface.

Key Features
Fake News Classification: Predicts whether the given news article is fake or real.
Prediction Probability: Displays the probability score for each prediction.
Bulk Upload: Allows users to upload a file containing multiple news articles for batch prediction.
Streamlit-based UI: Provides a simple and clean user interface for interaction.
🛠️ How It Works
Dataset Collection

The project uses the Kaggle Fake News Dataset, which contains news articles labeled as either real or fake. We further expand the dataset by incorporating additional real-world news sources to improve model performance.
Data Preprocessing

The dataset is preprocessed by cleaning the text, which includes removing stop words, punctuation, and irrelevant characters.
Text normalization techniques like stemming and lemmatization are applied to reduce words to their base forms.
Feature Engineering

The text data is converted into a numerical format using techniques like TF-IDF Vectorization. This allows the machine learning model to interpret the textual data effectively.
Model Building

We use Logistic Regression and Random Forest classifiers for fake news detection.
These models are trained using the Scikit-Learn library, and we fine-tune their parameters to optimize accuracy.
Model Evaluation

The models are evaluated using performance metrics such as accuracy, precision, recall, and F1-score to ensure reliable predictions.
Streamlit Application

The interactive web application is built using Streamlit, allowing users to upload news articles and view predictions with corresponding probabilities.
Users can input a single news article or upload a bulk file, and the system will predict whether each article is fake or real.
📊 Model Performance
After training the models, Logistic Regression and Random Forest performed well in terms of accuracy and recall, effectively identifying fake news articles.

🚀 Demo and Deployment
The project is deployed on Streamlit Cloud, where users can interact with the system via a web interface.

