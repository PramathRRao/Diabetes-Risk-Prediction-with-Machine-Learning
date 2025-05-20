# Diabetes-Risk-Prediction-with-Machine-Learning


Overview: Using machine learning approaches, this study examines diabetes prevalence in relation to numerous demographic parameters such as age, income, and smoking behaviors. It comprises data pretreatment, feature engineering, exploratory data analysis (EDA), and predictive model training. The project is developed and performed using Databricks.

Requirements

Prerequisites:

 1.Databricks Workspace:Access to a Databricks workspace.
 2.Cluster Configuration: 
      i. Databricks Runtime Version: 10.4 LTS (or higher), which includes Spark 3.x and Python 3.x.
      ii. Minimum 4GB of memory for efficient execution.
 3.Libraries to Install:
      i. xgboost
      ii. pandas
      iii. matplotlib
      iv. seaborn
      v. scikit-learn
      vi. numpy
 To install these libraries:

   1.Go to the Cluster tab in Databricks.
   2.Click Libraries > Install New and add the required libraries.
 4.Dataset
 The dataset used for this project can be downloaded from the Zip File. Upload the dataset to your Databricks workspace:

   i. Go to the Data tab in Databricks.
   ii. Click Create Table > Upload File and upload the dataset.
   iii. Save the file path for reference in the notebook.
 5.Steps to Set Up and Run in Databricks
  i. Create a New Notebook:
  Go to the Workspace tab in Databricks.
  Create a new notebook and name it appropriately.
  ii. Attach the Notebook to a Cluster:
  Attach the notebook to a running cluster with the required runtime.
  iii. Set Up the Environment:
  Ensure all required libraries are installed on the cluster.
  Verify the dataset file path and update it in the notebook code if needed.
  iv. Run the Notebook:
  Import the provided .ipynb file into Databricks.
  Open the notebook and run the cells sequentially to preprocess the data, perform EDA, train models, and visualize results.
  v. View Outputs:
  The notebook generates graphs, model evaluation metrics (accuracy and ROC-AUC), and insights from the data.


