# OIBSIP

# Task 1: Iris Flower Classification

## Objective
Classify Iris flower species (Setosa, Versicolor, Virginica) using physical measurements of sepals and petals.

## Tech Stack
- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## Summary of Results
- **EDA & Key Insights:** Petal length and petal width show the highest discriminative power to separate species.
- **Models Evaluated:** Logistic Regression, K-Nearest Neighbours, Random Forest Classifier.
- **Best Model:** Logistic Regression achieved 100% accuracy on the test set.

---------------------------------------------------------------------------------------------------------------------------------------

# Task 4: Email Spam Detection

## Objective
Build an NLP binary classification pipeline to classify messages as Spam or Ham (legitimate).

## Tech Stack
- Python, Pandas, Scikit-Learn (TF-IDF Vectorizer, Multinomial Naive Bayes, Logistic Regression)

## Key Findings
- Text preprocessed with lowercasing, punctuation removal, and stopword filtering.
- TF-IDF vectorization converted text to numeric features.
- Precision was prioritized to avoid false positives (misclassifying legitimate emails as spam).

-----------------------------------------------------------------------------------------------------------------------------------------

# Task 5: Sales Prediction

## Objective
Predict sales outcomes based on advertising expenditures across TV, Radio, and Newspaper channels.

## Tech Stack
- Python, Pandas, Matplotlib, Seaborn, Scikit-Learn (Linear Regression, Random Forest Regressor)

## Key Findings
- Linear Regression achieved high $R^2$ performance.
- Feature importance analysis revealed Radio spend has the highest marginal return per dollar spent, followed closely by TV. Newspaper spend showed minimal impact.
