
# Credit Risk Evaluator

This is a Python-based project that compares the performance of Logistic Regression and Random Forest Classifier models in predicting loan approval status. The project uses lending data to train and test the models, and evaluates their accuracy.

## Data

The data used in this project is stored in a CSV file called `lending_data.csv`. The data is imported using Pandas and the resulting DataFrame is used for model training and testing.

## Models

Two models are created, fitted, and scored on the data:

1. Logistic Regression
2. Random Forest Classifier

## Model Comparison

The project compares the performance of the Logistic Regression and Random Forest Classifier models by printing their scores. The model with a higher score is considered to have performed better.

## Dependencies

The following Python libraries are required to run this project:

* numpy
* pandas
* pathlib
* sklearn (train_test_split, LogisticRegression, RandomForestClassifier, mean_squared_error)

## How to run

To run this project, execute the code in the given order in a Python environment with the necessary libraries installed. The final output will display the model scores for both Logistic Regression and Random Forest Classifier models.

## Findings

The project concludes that the Logistic Regression model performs better than the Random Forest Classifier model in terms of beinng more notabily computational efficiency.

```
Logistic Regression:
Training Model Score: 0.9921240885954051
Testing Model Score: 0.9918489475856377
Score Delta: 0.0002751410097674434
```

```
RandomForestClassifier
Training Classifier Score: 0.9975409272252029
Testing Classifier Score: 0.9917457697069748
Score Delta: 0.005795157518228122
```
