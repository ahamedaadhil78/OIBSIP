# Iris Flower Classification

## Project Overview

This project uses Machine Learning to classify Iris flowers into three species:

- Setosa
- Versicolor
- Virginica

The classification is performed using flower measurements such as sepal length, sepal width, petal length, and petal width.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models

Three classification algorithms were used:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest

## Dataset

The Iris dataset was loaded using Scikit-learn's built-in Iris dataset.

The dataset contains:

- 150 samples
- 4 input features
- 3 flower species

## Data Preprocessing

The dataset was checked for:

- Missing values
- Data types
- Descriptive statistics
- Class distribution

Exploratory Data Analysis was performed using pair plots and box plots.

## Train-Test Split

The dataset was divided into:

- Training data: 80% (120 samples)
- Testing data: 20% (30 samples)

## Model Evaluation

The models were evaluated using accuracy, confusion matrix, and classification report.

### Accuracy Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 100% |
| KNN | 100% |
| Random Forest | 100% |

## Feature Importance

Random Forest feature importance showed that:

- Petal length
- Petal width

were the most important features for classification.

## Conclusion

The Iris flower dataset was successfully classified using Machine Learning techniques. All three models achieved 100% accuracy on the test set.

The project demonstrates how Machine Learning classification algorithms can be used to identify Iris flower species from their physical measurements.

## Project Structure

```text
Iris_Flower_Classification/
│
├── Iris_Flower_Classification.ipynb
└── README.md
