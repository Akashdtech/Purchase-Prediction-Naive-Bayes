# Purchase-Prediction-Naive-Bayes
This project demonstrates a basic binary classification pipeline to predict whether users will make a purchase based on demographic and behavioral data. The pipeline includes data preprocessing, feature scaling, and a Naive Bayes classification model.

Data Exploration:

    Load the dataset and examine its structure, summary statistics, and size.
    Display the first and last 10 records for an overview of the data.

Data Preprocessing:

    Removal of irrelevant features, such as User ID.
    Encoding of categorical variables (e.g., mapping gender to binary values).

Feature Preparation:

    Separate the data into features (X) and target variable (y).
    Split the data into training and testing sets using an 80/20 split.

Feature Scaling:

    Normalize the features using StandardScaler for improved model performance.

Model Training and Evaluation:

    Train a Gaussian Naive Bayes classifier on the scaled training data.
    Evaluate the model using metrics such as accuracy, a classification report, and a confusion matrix.

This project serves as an introduction to machine learning workflows, using Naive Bayes for classification tasks with continuous and categorical features.
