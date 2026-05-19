# WhatsApp Review Sentiment Analysis using NLP

## Project Overview

This project performs **Sentiment Analysis** on WhatsApp user reviews using **Natural Language Processing (NLP)** techniques. The model classifies reviews as **Positive** or **Negative** using **TF-IDF Vectorization** and **Logistic Regression**.

The project demonstrates how machine learning can analyze customer opinions and predict sentiments from textual data.

---

# Objective

* Perform sentiment analysis on WhatsApp reviews
* Apply NLP preprocessing techniques
* Convert text into numerical vectors using TF-IDF
* Train a Logistic Regression model
* Predict sentiments of customer reviews
* Evaluate model performance

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* NLTK
* Scikit-Learn

---

# Machine Learning Concepts Used

## Natural Language Processing (NLP)

Used for:

* Text cleaning
* Stopword removal
* Stemming
* Text preprocessing

---

# TF-IDF Vectorization

TF-IDF converts text into numerical vectors for machine learning models.

Formula:

```text
TF-IDF(t,d) = TF(t,d) × IDF(t)
```

---

# Logistic Regression

Used as the classification algorithm to predict:

* Positive Sentiment
* Negative Sentiment

---

# Dataset

The dataset contains WhatsApp customer reviews with sentiment labels.

Example:

| Review                  | Sentiment |
| ----------------------- | --------- |
| Excellent messaging app | Positive  |
| App crashes frequently  | Negative  |

---

# Project Workflow

```text
Dataset Collection
        ↓
Text Preprocessing
        ↓
TF-IDF Vectorization
        ↓
Train-Test Split
        ↓
Logistic Regression Model
        ↓
Prediction
        ↓
Model Evaluation
```

---

# Steps Performed

1. Import Required Libraries
2. Load WhatsApp Reviews Dataset
3. Perform Text Preprocessing
4. Remove Stopwords and Apply Stemming
5. Convert Text into TF-IDF Vectors
6. Split Dataset into Training and Testing Data
7. Train Logistic Regression Model
8. Predict Review Sentiments
9. Evaluate Model Accuracy
10. Visualize Sentiment Distribution

---

# Model Evaluation

The model performance is evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

# Output

The project generates:

* Predicted sentiments
* Accuracy score
* Confusion matrix
* Classification report
* Sentiment distribution graph

---

# Example Prediction

Input Review:

```text
WhatsApp video calling is excellent
```

Predicted Output:

```text
Positive
```

---

# Required Libraries

Install dependencies using:

```bash
pip install pandas numpy matplotlib nltk scikit-learn
```

---

# How to Run the Project

1. Open Jupyter Notebook or Google Colab
2. Install required libraries
3. Run all cells step-by-step
4. View outputs and predictions

---

# Applications of Sentiment Analysis

* Product Review Analysis
* Customer Feedback Analysis
* Social Media Monitoring
* Brand Reputation Analysis
* Movie Review Classification

---

# Conclusion

The project successfully implements Sentiment Analysis on WhatsApp reviews using NLP techniques. TF-IDF Vectorization and Logistic Regression effectively classify reviews into positive and negative sentiments with good accuracy.

---


