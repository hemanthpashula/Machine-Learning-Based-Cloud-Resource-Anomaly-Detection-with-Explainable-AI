# Cloud Resource Usage Dataset for Anomaly Detection using Machine Learning and Explainable AI

## Description

This project develops a machine learning framework for detecting anomalies in cloud resource usage and interpreting model predictions using SHAP and LIME. Four models Decision Tree, Random Forest, Gradient Boosting, and XGBoost are evaluated using the cloud anomaly dataset.

## Dataset

The project uses the publicly available **Cloud Anomaly Data** dataset from Kaggle:

[Cloud Anomaly Data – Kaggle](https://www.kaggle.com/datasets/sandhyapeesara/cloud-anomaly-data)

## How to Execute the Notebook

1. Open **Google Colab** and upload the `.ipynb` file.
2. Download the dataset from the Kaggle link above.
3. Upload **`Cloud_Anomaly_Dataset.csv`** to the Google Colab session.
4. Open the notebook and run the cells sequentially from top to bottom.
5. The notebook installs/imports the required libraries, loads and preprocesses the dataset, performs exploratory analysis, trains the four machine learning models, evaluates their performance, and generates SHAP and LIME explanations.
6. Review the generated accuracy results, classification reports, confusion matrices, model comparison, SHAP plots, and LIME explanation.

**Platform:** Google Colab
**Language:** Python
**Dataset File:** `Cloud_Anomaly_Dataset.csv`
