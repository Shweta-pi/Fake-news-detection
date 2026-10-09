# 📰 Fake News Detection using Machine Learning & Natural Language Processing (NLP)

A Machine Learning and Natural Language Processing (NLP) based classification project designed to identify and detect fake or misleading news articles. This application processes news content, extracts text features, and classifies the input as either **REAL** or **FAKE**.

---

## 📌 Features

- **Text Preprocessing & Data Cleaning:** Cleans input text using regular expressions, removal of stopwords, lowercasing, and stemming/lemmatization.
- **Feature Extraction:** Converts raw text into numerical representation using **TF-IDF (Term Frequency - Inverse Document Frequency)** vectorization.
- **Machine Learning Classification:** Trained using classification algorithms (e.g., Logistic Regression / Passive Aggressive Classifier / Naive Bayes) to achieve high accuracy.
- **Real-time Prediction:** Takes text or news titles as input and returns instant classification with confidence scores.
- **Interactive UI (Optional):** Easy-to-use web interface built using **Streamlit** / **Flask**.

---

## 📁 Repository Structure

```text
Fake-news-detection/
│── data/
│   ├── train.csv          # Training dataset
│   └── test.csv           # Testing dataset
│── notebooks/
│   └── Model_Training.ipynb  # Exploratory Data Analysis & Model Training
│── src/
│   ├── preprocess.py      # Text preprocessing helper functions
│   └── predict.py         # Prediction pipeline script
│── app.py                 # Streamlit / Flask web application entry point
│── model.pkl              # Saved Machine Learning Model
│── vectorizer.pkl         # Saved TF-IDF Vectorizer
│── requirements.txt       # Project dependencies
└── README.md              # Project documentation
⚙️ Tech Stack & Libraries
Language: Python 3.x

Libraries:

pandas & numpy (Data manipulation)

scikit-learn (Machine learning algorithms, TF-IDF, evaluation metrics)

nltk (Natural Language Toolkit for text processing and stopwords)

streamlit or flask (Web application interface)

matplotlib & seaborn (Data visualization & confusion matrix)
