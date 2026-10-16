# Loan Approval Using KNN Classification

## About the Project

This project uses K-Nearest Neighbors (KNN) Classification to predict whether a loan is given based on existing loans and credit score.The model is trained using loan data and classifies outcomes based on the input features. It also visualizes the decision boundaries to understand how the model separates different classes.I built this project to understand machine learning concepts, including data preprocessing, feature scaling, model training, classification, and visualization.

## Technologies Used

- **Python** – Programming language
- **Pandas** – Loading and handling the dataset
- **NumPy** – Numerical operations
- **Matplotlib** – Visualizing classification results
- **Scikit-learn** – Training and evaluating the KNN model

## How It Works

1. Load the loan dataset using Pandas.
2. Separate the input features and target variable.
3. Split the dataset into training and testing sets.
4. Standardize the input features using StandardScaler.
5. Train a KNN Classification model with 5 neighbors.
6. Predict loan outcomes for the test data.
7. Evaluate the model using a confusion matrix and accuracy score.
8. Visualize the training and testing decision boundaries.

## Model Used

**K-Nearest Neighbors (KNN) Classification**

KNN is a supervised machine learning algorithm that classifies a data point based on the classes of its nearest neighbors.This project uses 5 neighbors and Euclidean distance to classify loan outcomes based on existing loans and credit score.

## Visualizations

The project displays the training and testing classification results using decision boundary plots.

- **Red and green regions** represent predicted classes.
- Data points show the actual loan outcomes.

## Dataset

The project uses `Loan Distribution KNN Classification.csv`, which contains 226 records and the following columns:

- **Existing Loans** – Number of existing loans
- **Credit Score** – Credit score value
- **Loan Given** – Target class indicating the loan outcome

## What I Learned

- Understanding KNN Classification.
- Loading and handling datasets using Pandas.
- Splitting data into training and testing sets.
- Standardizing features using StandardScaler.
- Evaluating classification models using a confusion matrix and accuracy score.
- Visualizing decision boundaries using Matplotlib.
