# Anomaly Detection Project


Anomaly Detection via PyCaret Project Overview:

This project provides a comprehensive guide to unsupervised anomaly detection using the PyCaret machine learning library. 
The goal is to identify and analyze unusual patterns or outliers within a dataset by applying a variety of models, comparing their performance, and visualizing their results.

The notebook follows a clear, step-by-step process to perform the anomaly detection analysis:

    Import Data and Exploratory Analysis: The process begins with importing a dataset. An initial exploratory analysis is performed to understand the data's structure and characteristics before any modeling takes place.

    Setup PyCaret Environment: The PyCaret environment is set up specifically for anomaly detection. This step automatically handles crucial preprocessing tasks such as missing value imputation, scaling, and feature engineering.

    Select and Create Models: The notebook demonstrates how to create and train multiple anomaly detection models (e.g., Isolation Forest, Local Outlier Factor, K-Nearest Neighbors).

    Compare Model Anomalies: The trained models are used to predict anomalies, and the results from different models are compared to evaluate their effectiveness and identify consensus in their predictions.

    Visualize, Interpret Decisions & Save the Model: The anomalies are visualized to gain a deeper understanding of their nature. The final, best-performing model is saved for future use, allowing it to be easily loaded and applied to new data.


Files:

    Anomaly Detection via PyCaret.ipynb
    
    IForest_Model.pkl: The saved Isolation Forest model file

    LOF_Model.pkl: The saved Local Outlier Factor model file.

