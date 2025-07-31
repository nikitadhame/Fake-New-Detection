# Fake-New-Detection
Fake News Detection using Machine Learning
This project is a simple machine learning model to detect whether a news article is real or fake. It uses basic text preprocessing and classification techniques, making it beginner-friendly and easy to understand.

Overview
In the digital age, fake news can spread rapidly. This project aims to build a machine learning model that classifies news articles as real or fake based on their textual content.

The model was trained using a dataset of labeled news headlines and bodies, with text processing techniques like TF-IDF, and classification using Logistic Regression.

Technologies Used
Python

Jupyter Notebook

Scikit-learn

Pandas

Numpy

TF-IDF Vectorizer

Model
The machine learning pipeline includes:

Text Cleaning: Removing punctuation, converting to lowercase, and stripping stopwords.

Feature Extraction: TF-IDF vectorization.

Model Training: Logistic Regression Classifier.

Evaluation: Accuracy score, confusion matrix, and classification report.

Project Structure
csharp
Copy
Edit
Fake News Detection/
│
├── Fake News Detection using machine learning.ipynb  # Main notebook
├── README.md                                         # Project description
└── Dataset/                                          # (Optional) Dataset used

Results
The model achieved good accuracy on the test set. It can be further improved using:

More complex models (e.g., Random Forest, BERT)

Better text preprocessing

Larger and more diverse datasets


Future Improvements
Use deep learning models like LSTM or BERT

Build a web interface using Flask or Streamlit

Add real-time news checking via an API

About Me
My Name is Nikita Dhame  exploring the applications of machine learning in real-world problems. This project was done as part of my learning journey in NLP and model building.

