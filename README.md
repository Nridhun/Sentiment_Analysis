# Emotion Classification using Machine Learning

## Project Overview

This project is about classifying emotions from text using Machine Learning.

The dataset contains text comments and their corresponding emotions.

The emotions in the dataset are:

- Anger
- Fear
- Joy

Two Machine Learning models were trained and compared:

- Naive Bayes
- Support Vector Machine (SVM)

## Dataset

The dataset contains **5,937 text samples** and **2 columns**:

- `Comment` – Text comment
- `Emotion` – Emotion label

There are no missing values or duplicate rows in the dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preprocessing

The following preprocessing steps were performed:

1. Converted text to lowercase.
2. Removed punctuation and special characters.
3. Tokenized the text into words.
4. Removed English stopwords.

These steps helped to clean the text before applying machine learning models.

## Feature Extraction

**TF-IDF (Term Frequency-Inverse Document Frequency)** was used to convert text into numerical features.

The TF-IDF vectorizer created **7,733 features** from the training data.

## Machine Learning Models

### 1. Naive Bayes

Naive Bayes was used as the first classification model.

**Accuracy:** 89.06%

**F1 Score:** 89.06%

### 2. Support Vector Machine (SVM)

SVM was used as the second classification model.

**Accuracy:** 94.11%

**F1 Score:** 94.10%

## Model Comparison

| Model | Accuracy | F1 Score |
|---|---:|---:|
| Naive Bayes | 89.06% | 89.06% |
| SVM | 94.11% | 94.10% |

## Result

SVM performed better than Naive Bayes.

SVM achieved **94.11% accuracy**, while Naive Bayes achieved **89.06% accuracy**.

Therefore, **SVM was selected as the better model for this dataset**.

## Conclusion

In this project, we classified emotions from text using Machine Learning.

The text was cleaned and converted into numerical features using TF-IDF.

Two models were tested: Naive Bayes and SVM.

SVM performed better than Naive Bayes, so it is the preferred model for this emotion classification task.

## Project Files

- `Sentiment_Analysis.ipynb` – Jupyter Notebook containing the complete project
- `nlp_dataset.csv` – Dataset

## Author

**Nridhun V S**
