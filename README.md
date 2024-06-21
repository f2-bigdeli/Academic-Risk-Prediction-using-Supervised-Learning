# Academic Risk Prediction using Supervised Learning

This project aims to predict the academic risk of students in higher education using various supervised learning models. The dataset includes features such as demographic information, previous academic performance, and other relevant factors. The goal is to classify students into categories such as "Dropout," "Enrolled," or "Graduate".

## Project Structure

- `train.csv`: Training dataset containing features and target labels.
- `test.csv`: Test dataset for making predictions.
- `test_predictions.csv`: Predicted labels for the test dataset.
- `SupervisedModeling.ipynb`: Jupyter notebook containing the data preprocessing, model training, evaluation, and prediction code.

## Models Used

The following supervised learning models were used and evaluated in this project:
- Logistic Regression
- Random Forest
- Gradient Boosting
- K-Nearest Neighbors
- Support Vector Machine

## Evaluation Metrics

The models were evaluated using cross-validation with the following metrics:
- Accuracy
- Precision
- Recall
- F1-score

## Results

The best model was selected based on the highest mean F1-score from cross-validation. The selected model was then used to make predictions on the test dataset.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/f2-bigdeli/Academic-Risk-Prediction-using-Supervised-Learning.git
   cd academic-risk-prediction
