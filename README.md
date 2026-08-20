# IMDb Sentiment Analysis

A machine learning project for classifying IMDb movie reviews as **positive** or **negative** using Natural Language Processing (NLP) and machine learning techniques.

## 📌 Project Overview

This project performs sentiment analysis on IMDb movie reviews.

The dataset contains **50,000 labeled movie reviews**:

- 25,000 Positive reviews
- 25,000 Negative reviews

The data is split into training and testing sets using an **80/20 split**.

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

1. Load and inspect the IMDb dataset.
2. Check the data and sentiment distribution.
3. Clean and prepare the review text.
4. Split the data into training and testing sets.
5. Convert text into numerical features using TF-IDF.
6. Train machine learning classification models.
7. Evaluate model performance.
8. Compare the results.

## 🤖 Machine Learning Models

### Logistic Regression

Logistic Regression is used for binary sentiment classification.

### Linear SVM

Linear Support Vector Machine (Linear SVM) is used for text classification and model comparison.

## 📊 Results

The best achieved accuracy on the test data was:

### **91.1% Accuracy**

The model successfully classifies IMDb movie reviews into positive and negative sentiment categories.

## 📈 Evaluation

Model performance is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

## 📚 Dataset

This project uses the **IMDb Large Movie Review Dataset**.

The dataset contains 50,000 labeled movie reviews:

- 25,000 Positive reviews
- 25,000 Negative reviews

### Download Dataset

You can download the `IMDB Dataset.csv` file from Zenodo:

[Download IMDB Dataset.csv](https://zenodo.org/records/7929635)

After downloading, place the dataset in the project directory:

```text
sentiment-analysis-imdb/
│
├── IMDB Dataset.csv
├── README.md
├── requirements.txt
└── sentiment_analysis.ipynb


Then open sentiment_analysis.ipynb and run the cells from top to bottom.

Original Dataset

The original Large Movie Review Dataset was created by Maas et al. (2011).

Official Stanford Dataset

📂 Project Structure
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
3. Download the dataset

Download IMDB Dataset.csv from the dataset link above and place it in the project directory.

4. Open the notebook
jupyter notebook sentiment_analysis.ipynb
5. Run the notebook

Run the cells from top to bottom to reproduce the analysis and results.

🎯 Conclusion

This project demonstrates how Natural Language Processing and machine learning can be used for sentiment analysis.

Using TF-IDF features and machine learning classification models, the project achieved an accuracy of 91.1% on the test data.




Author: Ronika-kh
