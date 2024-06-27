# Credit-Defaults-AI
This repository is the official implementation of Predicting Credit Card Defaulting Using Machine Learning

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Training and Evaluation](#training-and-evaluation)
- [Results](#results)
- [License](#license)
- [Citation](#citation)
- [Contributing](#contributing)

## Dataset

The dataset used in this project is the [Default of Credit Card Clients Dataset](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients) provided by the UCI Machine Learning Repository.

### Dataset Access

The dataset can be accessed from the UCI Machine Learning Repository at the following DOI: [10.24432/C55S3H](https://doi.org/10.24432/C55S3H).

### License and Access Restrictions

The dataset is available under the terms provided by the UCI Machine Learning Repository. For detailed information, please refer to the [UCI repository license](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients#license).

There are no additional access restrictions.

### Metadata

The dataset adheres to Schema.org metadata standards and includes the following information:
- **Title**: Default of Credit Card Clients Dataset
- **Author(s)**: UCI Machine Learning Repository
- **Description**: This dataset contains information on default payments, demographic factors, credit data, and payment history of credit card clients in Taiwan.
- **Keywords**: Credit Card, Default, Financial Risk, UCI Machine Learning Repository
- **Date of Publication**: October 2008
- **Version**: 1.0
- **License**: Refer to the [UCI repository license](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients#license)
- **DOI**: [10.24432/C55S3H](https://doi.org/10.24432/C55S3H)

## Training and Evaluation 

The training and evaluation processes for the models used in this project (XGBoost, SVC, and Keras) are comprehensively documented in the provided Google Colab notebooks. Below are brief descriptions and links to each notebook for detailed steps and implementation:

**XGBoost Model**
The [XGBoost notebook](https://github.com/Boxika/Credit-Defaults-AI/blob/main/Notebooks/XGBoost_Train_and_Evaluate.ipynb) includes the following steps:

- Data loading and preprocessing.
- Applying SMOTE for handling class imbalance.
- Hyperparameter tuning using GridSearchCV.
- Training the XGBoost model with the best parameters.
- Evaluation using various metrics and visualizations.

**Support Vector Classifier (SVC)**
The [SVC notebook](https://github.com/Boxika/Credit-Defaults-AI/blob/main/Notebooks/Support_Vector_Classification_Train_and_Evaluate.ipynb) covers:

- Data loading and preprocessing.
- Handling class imbalance with class weights.
- Hyperparameter tuning using GridSearchCV.
- Training the SVC model with the optimal parameters.
- Evaluation through metrics like accuracy, confusion matrix, classification report, and ROC-AUC score.

**Keras (TensorFlow) Model**
The [Keras notebook](https://github.com/Boxika/Credit-Defaults-AI/blob/main/Notebooks/Keras_Train_and_Evaluate.ipynb) details:

- Data loading and preprocessing.
- Building and compiling a neural network model.
- Training with early stopping to avoid overfitting.
- Evaluating model performance with various metrics and plotting the ROC curve.

