# Titanic-Classification
# Titanic Dataset Analysis and Survival Prediction

This "Read Me" file provides an overview of two code snippets for analyzing the Titanic dataset and predicting passenger survival using a Random Forest Classifier.

## Code Snippet 1

### Purpose
Predict passenger survival on the Titanic.

### Steps
1. Import necessary libraries.
2. Load the Titanic dataset from a CSV file.
3. Preprocess the data, including handling missing values and creating dummy variables for 'Pclass'.
4. Split the dataset into training and testing sets.
5. Create a Random Forest Classifier and train it.
6. Make predictions on the test data and evaluate the model.

### Results
- Model Accuracy: 81.01%
- Classification Report:
-           precision    recall  f1-score   support

       0       0.83      0.86      0.84       105
       1       0.79      0.74      0.76        74

accuracy                           0.81       179

- Validation Accuracy: 79.33%
