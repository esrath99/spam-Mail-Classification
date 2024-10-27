# spam-Mail-Classification Using Machine Learning Techniques

# Objective
To build a machine learning model that accurately classifies email messages as either "Spam" or "Not Spam (Ham)

# Project Workflow

**Data Loading & Preprocessing**: Load dataset, check for missing values and duplicates, and filter relevant categories ('ham' & 'spam').
**Exploration**: Visualize category distribution and generate word clouds to identify key terms in spam and ham messages.
**Feature Extraction**: Convert email text into numerical data using CountVectorizer.
**Balancing Data**: Apply SMOTE to handle data imbalance between spam and ham categories.
**Data Splitting**: Split the data into training and testing sets (80/20).
**Model Building**: Train a Naive Bayes model (BernoulliNB) on the data.
**Evaluation**: Assess model accuracy and visualize the confusion matrix to understand classification performance.
