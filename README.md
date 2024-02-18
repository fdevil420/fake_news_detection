# Fake News Detection using Python

This project aims to detect fake news using Python. It employs Natural Language Processing (NLP) techniques and a machine learning model to classify news articles as either real or fake.

## Installation

Clone the repository:

```bash
git clone https://github.com/fdevil420/fake-news-detection.git

Navigate to the project directory: cd fake-news-detection
Install the required dependencies: pip install -r requirements.txt

Usage:
Ensure you have Python installed on your system. You can run the project by executing the following command: python fake_news_detection.py
Dependencies:
numpy
pandas
nltk
scikit-learn

How It Works
Data Preprocessing: The dataset is preprocessed by removing unnecessary characters, converting text to lowercase, and applying stemming.

Feature Extraction: Text data is converted into numerical vectors using the TF-IDF (Term Frequency-Inverse Document Frequency) technique.

Model Training: The Logistic Regression model is trained on the preprocessed data.

Evaluation: The model's accuracy is evaluated using the test dataset.
