# IMDb Sentiment Analysis

A machine learning project for classifying IMDb movie reviews as **positive** or **negative**.

## 📌 Project Overview

This project performs sentiment analysis on IMDb movie reviews using Natural Language Processing (NLP) and machine learning techniques.

The dataset contains **50,000 movie reviews** with two sentiment classes: positive and negative. The data is split into training and testing sets using an 80/20 ratio.

## 🧠 Methods

The project uses:

* **TF-IDF** for text feature extraction
* **Logistic Regression**
* **Linear SVM (LinearSVC)**
* **Scikit-learn Pipelines**
* Classification Report
* Confusion Matrix

For TF-IDF, the project uses English stop-word removal, up to 20,000 features, and word n-grams ranging from 1 to 2.

## 📊 Dataset

The dataset contains:

* **50,000 reviews**
* **25,000 positive reviews**
* **25,000 negative reviews**
* 2 columns: `review` and `sentiment`

There are no missing values in the dataset.

## 📈 Results

| Model               |   Accuracy |
| ------------------- | ---------: |
| Logistic Regression | **90.01%** |
| Linear SVM          | **90.52%** |

The **Linear SVM** achieved the best accuracy in this project.

### Linear SVM Confusion Matrix

```text
[[4488  512]
 [ 436 4564]]
```

## 🔎 Example Predictions

The trained models were also tested on custom reviews such as:

* `"i hate that"`
* `"that was terrible"`

The models were able to classify these sample reviews as negative.

## 🛠️ Technologies

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook
* NLP
* Machine Learning

## 📂 Project Structure

```text
sentiment-analysis-imdb/
│
├── sentiment_analysis.ipynb
└── README.md
```

## 🚀 How to Run

1. Clone this repository.
2. Make sure the IMDb dataset is available in the project directory.
3. Install the required Python libraries.
4. Open `sentiment_analysis.ipynb` using Jupyter Notebook or JupyterLab.
5. Run the notebook cells.

## 👩‍💻 Author

**Ronika-kh**

GitHub: [Ronika-kh](https://github.com/Ronika-kh)
