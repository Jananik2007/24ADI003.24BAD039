**Naïve Bayes Classification Projects**

This repository contains two machine learning classification projects implemented using Naïve Bayes algorithms:

**Multinomial Naïve Bayes – SMS Spam Detection**

**Gaussian Naïve Bayes – Iris Flower Classification**

Both projects demonstrate preprocessing, model training, evaluation, visualization, and performance analysis.

**Scenario 1 – Multinomial Naïve Bayes**
SMS Spam Classification
**Problem Statement**

Classify SMS messages as Spam or Ham (Not Spam) using text classification techniques.

**Dataset**

Name: SMS Spam Collection Dataset

Source: Kaggle (UCI Public Dataset)

Target Variable: Message Label (Spam / Ham)

Input Feature: SMS Text Messages

**Project Workflow**
1️.Data Preprocessing

Converted text to lowercase

Removed punctuation

Removed stopwords (optional)

Cleaned and normalized text data

2️.Feature Extraction

Converted text into numerical representation using:

Count Vectorization

TF-IDF Vectorization

3️.Model Building

Encoded target labels (Spam = 1, Ham = 0)

Split dataset into training and testing sets

Trained Multinomial Naïve Bayes classifier

Applied Laplace Smoothing

4️.Model Evaluation

Performance evaluated using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

5️.Analysis

Misclassified message inspection

Top spam-indicating words (Feature importance)

Word frequency comparison (Spam vs Ham)

Impact of Laplace smoothing

**Visualizations**

Confusion Matrix

Top Influential Spam Words

Word Frequency Comparison

TF-IDF Feature Importance

**Scenario 2 – Gaussian Naïve Bayes**
Iris Flower Classification
**Problem Statement**

Classify flower species based on physical measurements.

**Dataset**

Name: Iris Dataset

Source: sklearn built-in dataset

Target Variable: Flower Species

Input Features:

Sepal Length

Sepal Width

Petal Length

Petal Width

**Project Workflow**
1️.Data Inspection & Preprocessing

Checked for missing values

Data exploration and visualization

Applied feature scaling (Standardization)

2️.Model Building

Split dataset into training and testing sets

Trained Gaussian Naïve Bayes classifier

Predicted species labels

3️.Model Evaluation

Evaluated using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

4️.Advanced Analysis

Compared predicted vs actual labels

Analyzed class probabilities

Compared with Logistic Regression (optional)

**Visualizations**

Decision Boundary Plot (2D features)

Confusion Matrix

Probability Distribution Plots

**Conclusion**

This repository demonstrates practical implementation of:

Multinomial Naïve Bayes for text classification

Gaussian Naïve Bayes for continuous numerical data

It highlights the strength of probabilistic classifiers in both NLP and structured datasets.
