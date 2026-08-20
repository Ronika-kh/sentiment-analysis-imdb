# IMDb Sentiment Analysis

A machine learning project for classifying IMDb movie reviews as **positive** or **negative** using Natural Language Processing (NLP) and machine learning techniques.

## 📌 Project Overview

This project performs sentiment analysis on IMDb movie reviews using Natural Language Processing (NLP) and machine learning techniques.

The dataset contains **50,000 movie reviews** with two sentiment classes:

- Positive
- Negative

The data is split into training and testing sets using an **80/20 ratio**.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- TF-IDF Vectorization
- Logistic Regression
- Linear SVM

## 🔍 Methodology

The project follows these main steps:

1. Load and explore the IMDb dataset.
2. Prepare the review text and sentiment labels.
3. Split the dataset into training and testing sets.
4. Convert text reviews into numerical features using **TF-IDF**.
5. Train machine learning classification models.
6. Evaluate the models using accuracy, classification reports, and confusion matrices.
7. Compare the classification results.

## 🤖 Machine Learning Models

### Logistic Regression

Logistic Regression is used as a linear classification model to predict whether a movie review is positive or negative.

### Linear SVM

Linear Support Vector Machine (Linear SVM) is also used for text classification and comparison with Logistic Regression.

## 📊 Results

The best achieved classification accuracy was:

### **91.1% Accuracy**

This result shows that the model can effectively classify IMDb movie reviews into positive and negative sentiment categories.

## 📈 Evaluation

The models are evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

These metrics provide an overview of the classification performance.

## 📂 Project Structure

```text
sentiment-analysis-imdb/
│
├── README.md
├── requirements.txt
└── sentiment_analysis.ipynb


🚀 How to Run
1. Clone the repository
git clone https://github.com/Ronika-kh/sentiment-analysis-imdb.git
2. Install the required libraries
pip install -r requirements.txt
3. Open the Jupyter Notebook
jupyter notebook sentiment_analysis.ipynb
4. Run the notebook

Make sure the IMDb dataset is available in the notebook's working directory, then run the cells in order.

📚 Dataset

The project uses the IMDb movie review dataset containing 50,000 labeled reviews.

Each review belongs to one of two sentiment classes:

positive
negative
🎯 Conclusion

This project demonstrates how Natural Language Processing and machine learning can be used to perform sentiment analysis on movie reviews.

Using TF-IDF features and machine learning classification models, the project achieved an accuracy of 91.1%.

Author: Ronika-kh
