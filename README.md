# Credit Default Prediction

This project aims to predict the likelihood of credit default in the Credit Default dataset. Two datasets are provided: `train.csv` (contains features and the binary target indicating credit default) and `test.csv` (contains only features). The goal is to build models to predict the credit default in the test dataset.

## Dataset

- **train.csv:** Contains features and the target variable indicating credit default.
- **test.csv:** Contains only features; predictions need to be made on this dataset.

## Models Used

The following machine learning models are used for credit default prediction:

- **Decision Tree Classifier**
- **Logistic Regression**
- **K-Nearest Neighbors Classifier**
- **Support Vector Classifier (SVC)**
- **XGBoost**
- **LightGBM**
- **CatBoost**

## Data Preprocessing

Data preprocessing techniques include:

- **Scaling:** StandardScaler and MinMaxScaler are applied to scale numerical features.
- **Train-Test Split:** The dataset is split into training and testing sets.
- **Cross-Validation:** StratifiedKFold, ShuffleSplit, and other cross-validation techniques are used.

## Model Evaluation

Model performance is evaluated using various metrics, including:

- **Classification Report**
- **F1 Score**
- **Precision**
- **Recall**
- **Accuracy**

## Hyperparameter Tuning

GridSearchCV and RandomizedSearchCV are employed for hyperparameter tuning to enhance model performance.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/credit-default-prediction.git
   cd credit-default-prediction
