# Titanic Survival Predictor

Developed a Logistic Regression classification model to predict passenger survival probability using the Titanic dataset.

## Objective

To predict whether a passenger survived or did not survive based on passenger information.

## Project Steps

1. Load the Titanic dataset.
2. Preprocess the data.
3. Handle missing values.
4. Convert categorical data into numerical data.
5. Split the dataset into training and testing data.
6. Train the Logistic Regression model.
7. Evaluate the model using accuracy and confusion matrix.
8. Save the trained model as a `.pkl` file.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib

## Machine Learning Model

- Logistic Regression

## Data Preprocessing

- Removed unnecessary columns.
- Filled missing Age and Fare values using the median.
- Filled missing Embarked values using the mode.
- Converted categorical values into numerical values using One-Hot Encoding.

## Model Evaluation

- Accuracy Score
- Confusion Matrix

## Saved Model

The trained model is saved as:

`PreservedTitanic.pkl`
