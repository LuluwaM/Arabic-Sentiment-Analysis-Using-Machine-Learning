# Arabic-Sentiment-Analysis-Using-Machine-Learning

## 📌 Project Overview

This project focuses on building a **Machine Learning model** to analyze sentiment in Arabic text and classify reviews into two categories:

- 🟢 Positive (1)
- 🔴 Negative (0)

The project uses **Natural Language Processing (NLP)** techniques to process and analyze Arabic text.

## 🎯 Objectives

- Build an accurate model for Arabic sentiment classification.
- Handle challenges specific to Arabic text.
- Evaluate model performance using multiple metrics.
- Improve performance through **Hyperparameter Tuning**.

## 🛠️ Methodology

### 1️⃣ Libraries

| Library | Usage |
|---|---|
| Pandas | Data processing and analysis |
| NLTK | Natural Language Processing |
| Scikit-learn | Machine Learning and evaluation |
| AraBERT | Arabic language modeling |

### 2️⃣ Data Preprocessing 🧹

- Removed missing values and duplicates.
- Cleaned Arabic text.
- Removed special characters, numbers, and URLs.
- Removed Arabic stopwords.

### 3️⃣ Text Vectorization 🔢

**TF-IDF** was used to convert text into numerical features.

### 4️⃣ Data Splitting 📊

- 🟦 Training Set: 80%
- 🟨 Test Set: 20%

### 5️⃣ Model Training 🤖

**Logistic Regression** was used to classify reviews into positive and negative sentiments.

### 6️⃣ Model Evaluation 📈

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 7️⃣ Hyperparameter Tuning ⚙️

Hyperparameter tuning was applied to optimize the model's performance.

## 📂 Dataset

**Arabic Sentiment Reviews – Kaggle**

The dataset contains approximately **330,000 Arabic reviews** classified into positive and negative sentiments.

| Attribute | Value |
|---|---:|
| Number of Reviews | 330,000 |
| Number of Columns | 2 |
| Number of Classes | 2 |
| Class Distribution | Relatively Balanced |

## 🏆 Results

| Metric | Score |
|---|---:|
| Train Accuracy | **91%** |
| Test Accuracy | **90%** |
| Precision | **90%** |
| Recall | **89%** |
| F1-Score | **90%** |

## 💡 Conclusion

The final model achieved **90% test accuracy**, demonstrating strong performance in classifying Arabic reviews into positive and negative sentiment categories.
