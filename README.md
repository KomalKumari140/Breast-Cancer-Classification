# Breast Cancer Classification Using Logistic Regression

## Project Overview

This project implements a machine learning classification model using **Logistic Regression** to classify breast cancer tumors as malignant or benign. It uses the Breast Cancer Wisconsin dataset available through Scikit-learn.

The notebook demonstrates the basic machine learning workflow, from loading the dataset to training and evaluating the classification model.

## Objectives

- Understand and implement Logistic Regression.
- Load and explore a real-world medical dataset.
- Split data into training and testing sets.
- Apply feature scaling using StandardScaler.
- Train a classification model and generate predictions.
- Evaluate model performance using classification metrics.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Scikit-learn

## Dataset

The project uses Scikit-learn's built-in Breast Cancer Wisconsin dataset, so a separate dataset download is not required.

The dataset contains numerical features computed from digitized images of breast mass samples. The target classes are:

- **Malignant:** Cancerous tumor
- **Benign:** Non-cancerous tumor

## Machine Learning Workflow

1. Import the required libraries.
2. Load the Breast Cancer Wisconsin dataset.
3. Separate the input features and target labels.
4. Split the data into training and testing sets.
5. Standardize the features using StandardScaler.
6. Train the Logistic Regression model.
7. Generate predictions on the test data.
8. Evaluate predictions using accuracy, classification report, and confusion matrix.

## Evaluation Metrics

The notebook uses:

- Accuracy Score
- Classification Report (precision, recall, and F1-score)
- Confusion Matrix

Actual performance values should be taken from the notebook's executed results.

## Project Structure

```text
Breast-Cancer-Classification/
└── LogisticRegression.ipynb
```

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas scikit-learn jupyter
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `LogisticRegression.ipynb` and run the cells.

## Disclaimer

This is an educational machine learning project. Its predictions are not intended for clinical use and should not be used to diagnose or guide treatment for any medical condition.

## Author

Komal Kumari
