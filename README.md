# News-Article-Classification-Real-fake-
Fake News Classification project using Natural Language Processing (NLP) and Machine Learning models (Logistic Regression &amp; Naive Bayes). Includes preprocessing, TF-IDF vectorization, model training, evaluation, and results.”
News Article Classification: Real vs Fake

Project Overview

This project classifies news articles as Real or Fake using Machine Learning and Natural Language Processing (NLP).
It includes data preprocessing, TF-IDF vectorization, model training (Logistic Regression & Naive Bayes), evaluation, and a Streamlit web app for real-time predictions.


---

Dataset

Dataset: fake_and_real_news.csv

Features:

Text: News article content

label: FAKE / REAL




---

Project Workflow

1. Data Loading – Load CSV dataset into pandas.


2. Preprocessing – Clean text (remove punctuation, lowercase, stopwords removal, lemmatization).


3. Vectorization – Convert text into numerical features using TF-IDF.


4. Model Training – Train Logistic Regression and Naive Bayes models.


5. Evaluation – Measure performance using accuracy, F1-score, and confusion matrix.


6. Deployment – Build Streamlit app to classify user-input news.


7. Save Models – Save models and vectorizer as .pkl files for reuse.




---

Installation

1. Clone the repository:



git clone <your-github-repo-url>
cd fake-news-classification

2. Install dependencies:



pip install -r requirements.txt


---

Usage

Train Models

python train_model.py

Preprocesses data, trains models, evaluates performance, and saves .pkl files.


Run Streamlit App

streamlit run app.py

Enter a news article and select the model to classify it as Fake or Real.



---

Results

Logistic Regression Accuracy: ~93%

Naive Bayes Accuracy: ~91%

Confusion matrices indicate strong classification performance for both classes.
