##WhatsApp Review Sentiment Analysis using NLP
#Project Overview

This project performs Sentiment Analysis on WhatsApp user reviews using Natural Language Processing (NLP) techniques. The model classifies reviews as Positive or Negative using TF-IDF Vectorization and Logistic Regression.

The project demonstrates how machine learning can analyze customer opinions and predict sentiments from textual data.

#Objective
Perform sentiment analysis on WhatsApp reviews
Apply NLP preprocessing techniques
Convert text into numerical vectors using TF-IDF
Train a Logistic Regression model
Predict sentiments of customer reviews
Evaluate model performance
#Technologies Used
Python
Pandas
NumPy
Matplotlib
NLTK
Scikit-Learn
#Machine Learning Concepts Used
#Natural Language Processing (NLP)

Used for:

Text cleaning
Stopword removal
Stemming
Text preprocessing
#TF-IDF Vectorization

TF-IDF converts text into numerical vectors for machine learning models.

Formula:

TF-IDF(t,d) = TF(t,d) × IDF(t)
#Logistic Regression

Used as the classification algorithm to predict:

Positive Sentiment
Negative Sentiment
#Dataset

The dataset contains WhatsApp customer reviews with sentiment labels.

Example:

Review	Sentiment
Excellent messaging app	Positive
App crashes frequently	Negative
#Project Workflow
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
#Steps Performed
Import Required Libraries
Load WhatsApp Reviews Dataset
Perform Text Preprocessing
Remove Stopwords and Apply Stemming
Convert Text into TF-IDF Vectors
Split Dataset into Training and Testing Data
Train Logistic Regression Model
Predict Review Sentiments
Evaluate Model Accuracy
Visualize Sentiment Distribution
#Model Evaluation

The model performance is evaluated using:

Accuracy Score
Confusion Matrix
Classification Report
#Output

The project generates:

Predicted sentiments
Accuracy score
Confusion matrix
Classification report
Sentiment distribution graph
#Example Prediction

Input Review:

WhatsApp video calling is excellent

Predicted Output:

Positive
#Required Libraries

Install dependencies using:

pip install pandas numpy matplotlib nltk scikit-learn
#How to Run the Project
Open Jupyter Notebook or Google Colab
Install required libraries
Run all cells step-by-step
View outputs and predictions
#Applications of Sentiment Analysis
Product Review Analysis
Customer Feedback Analysis
Social Media Monitoring
Brand Reputation Analysis
Movie Review Classification
#Conclusion

The project successfully implements Sentiment Analysis on WhatsApp reviews using NLP techniques. TF-IDF Vectorization and Logistic Regression effectively classify reviews into positive and negative sentiments with good accuracy.
