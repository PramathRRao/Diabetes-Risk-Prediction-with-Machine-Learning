# Diabetes-Risk-Prediction-with-Machine-Learning


## Overview
This project applies machine learning techniques to predict diabetes risk based on demographic and behavioral factors such as age, income, BMI, and smoking status. The pipeline includes data preprocessing, feature engineering, exploratory data analysis (EDA), model training, and evaluation. The entire project was developed and executed using the Databricks platform.

## Requirements

### Prerequisites
1. Databricks Workspace  
   Access to a Databricks account and workspace.

2. Cluster Configuration  
   - Databricks Runtime: Version 10.4 LTS or higher (includes Spark 3.x and Python 3.x)  
   - Minimum Memory: 4 GB RAM

3. Python Libraries Required  
   - xgboost  
   - pandas  
   - matplotlib  
   - seaborn  
   - scikit-learn  
   - numpy  

   To install libraries:  
   - Go to the Clusters tab in Databricks.  
   - Click "Libraries" > "Install New" and add the required libraries.
4. Dataset  
   - File: `diabetes_012_health_indicators_BRFSS2015.csv`  
   - Upload Instructions:  
     - Go to the Data tab in Databricks.  
     - Click "Create Table" > "Upload File" and upload the dataset.  
     - Save the file path to use in the notebook.

## Steps to Set Up and Run in Databricks

1. Create a New Notebook  
   - Go to the Workspace tab.  
   - Create a new Python notebook and give it an appropriate name.

2. Attach the Notebook to a Cluster  
   - Attach the notebook to a running cluster with required libraries installed.

3. Set Up the Environment  
   - Ensure all required libraries are installed on the cluster.  
   - Update the dataset file path in the notebook code if needed.

4. Run the Notebook  
   - Import the provided `.ipynb` file into Databricks.  
   - Open the notebook and run the cells sequentially to:  
     - Preprocess the data  
     - Perform EDA  
     - Train machine learning models  
     - Evaluate and visualize results

5. View Outputs  
   - The notebook generates plots and evaluation metrics including accuracy, precision, recall, and ROC-AUC.

## Outcomes

- Predictive models to classify diabetes risk based on survey data  
- Feature importance analysis identifying key risk factors  
- Visual analysis of diabetes prevalence patterns



