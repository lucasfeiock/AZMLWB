<head>
<title>Model Management</title>
</head>


# Azure Machine Learning Model Management

## Introduction
- Iris flower data set
- Machine Learning Classification Model
- Azure Machine Learning Model Management

## Prerequisites
- [Azure Free Trial Subscription] (https://azure.microsoft.com/en-us/free)
    - If you have an Azure subscription already, you can skip this step.

- [Azure Portal] (https://portal.azure.com/)
- Azure Machine Learning Workbench
    - [Install Workbench on Windows 10] (https://aka.ms/azureml-wb-msi)
    - [Install Workbench on macOS] (https://aka.ms/azureml-wb-dmg)
- [Model management command-line interface reference] (https://docs.microsoft.com/en-us/azure/machine-learning/preview/model-management-cli-reference)

## Iris flower data set
- <https://en.wikipedia.org/wiki/Iris_flower_data_set>

Ronald Fisher was a statistician and biologist who published the data set in a paper in 1936. The data was collected by Edgar Anderson who worked with Fisher at John Innes Horticultural Institute in Britain. Four features measured from each sample: the length and width of the sepals and petals, in centimetres. The data set is multivariate or having more than two variables. There is one feature that contains the type of species the sample is associated with, and used for classification.

## Machine Learning Classification 
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

