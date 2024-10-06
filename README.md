# Player Performance Prediction using Machine Learning

This project focuses on predicting player performance for the Phoenix Suns using various machine learning techniques. The goal is to provide insights that help optimize player acquisitions and enhance team strategies.

## Project Overview

The primary objective of this project is to analyze player statistics and predict their future performance using machine learning models. The project involves creating a robust pipeline that includes data collection, preprocessing, model development, and evaluation. The results are visualized using Power BI dashboards and various visualization tools.

## Technologies Used
- **Azure Machine Learning**: For model development and deployment.
- **VS Code**: For writing and debugging code.
- **Python**: Main language for data analysis and machine learning.
- **Jupyter Notebooks**: For interactive coding and model experimentation.
- **Power BI**: For data visualization and reporting.
- **GitHub**: For version control and collaboration.

## Steps Followed in the Project

### 1. Data Collection and Preprocessing
- Gathered player statistics and performance metrics from multiple sources (internal databases, APIs, etc.).
- Cleaned and preprocessed the data using pandas and NumPy.

### 2. Azure Machine Learning Workspace Setup
- Created an Azure ML Workspace.
  
  ![Azure ML Workspace Creation](AzureML_Workspace%20_creation.png)

- Configured necessary resources (Storage Account, Key Vault, etc.).

  ![Azure ML Subscription](Azure_ML_Subscription.png)

- Launched compute instances to run experiments and models.

  ![Compute Instances](Compute.png)

### 3. Model Development
- Used several machine learning techniques such as:
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Gradient Boosting Machines (GBM)
  - XGBoost
- Fine-tuned hyperparameters using Grid Search and Randomized Search.

### 4. Model Evaluation
- Evaluated the performance of each model using accuracy, precision, recall, and F1-score.
- Visualized the model performance and results in Jupyter Notebooks and Power BI.

### 5. Deployment
- Deployed the best-performing model using Azure ML for real-time predictions.
- Set up APIs for easy access to the predictions and integration with other systems.

  ![Deployment Completion](Deployment_Completion.png)

## Files in the Repository

- **Data_Science.ipynb**: Jupyter Notebook with the entire workflow of data analysis and model building.
- **player_stat.csv**: Dataset of player statistics used for the analysis.
- **Azure_ML_Workspace_creation.png**: Steps for creating Azure ML Workspace.
- **Compute.png**: Screenshot showing compute instance configuration.
- **Deployment_Completion.png**: Screenshot showing successful deployment of the model.
- **README.md**: This file, describing the project and the process.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/harshithach999/Player-Performance-Prediction.git
   cd Player-Performance-Prediction
