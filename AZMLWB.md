<head>
<title>Model Management</title>
</head>


# Azure Machine Learning Model Management

## Introduction
- Iris flower data set
- Machine Learning Classification
- Azure Machine Learning Model Management

## Prerequisites
- Azure Free Trial Subscription
- Azure Machine Learning Workbench
- Azure Command Line Interface

## Iris flower data set
- Ronald Fisher - statistician and biologist, published paper in 1936
- Measurements of each sample are length and width of the sepals and petals in centimetres
- images showing the flower and measurements
- Multivariate data set (two or more variables)
- Classify which of the three species of Iris is being measured using data

## Machine Learning Classification 
- Exploratory Data Analysis
    - 50 samples of three species of Iris 
        - Iris setosa
        - Iris virginica
        - Iris versicolor
    - Row counts
    - Type counts 
    - Scatter plot
- Logistic Regression 
    - sklearn.linear_model.LogisticRegression.html

## Azure Machine Learning Model Management
- Model pickle file
    - Python object serialization
    - Preserving food within water, vinegar, and salt is called pickling
    - Scoring and evaluating the model
- Operationalize
    - Azure Command Line Interface
    - az ml Python
    - Prepare a Docker image in Azure
    - Download and test localy
    - Deploy real-time web service
- Monitor Model Performance
    - Model Data in Blob Storage Account
    - CSV to download 
        - Azure Machine Learning Workbench
        - Power BI

