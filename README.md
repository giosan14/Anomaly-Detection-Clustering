# Fraud Detection and Anomaly Clustering

This repository contains Python code for comprehensive fraud detection and anomaly clustering techniques applied to credit card transaction data. The project focuses on detecting fraudulent activities and identifying outliers within transactional datasets using various anomaly detection algorithms and clustering techniques.

## Overview

Fraud detection and anomaly clustering are critical in the financial sector to identify irregular patterns and fraudulent transactions within large datasets. This project aims to provide a practical demonstration of anomaly detection and clustering techniques using real-world credit card transaction data.

## Dependencies

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Usage

1. Clone or download the repository.
2. Ensure that you have the required dependencies installed in your Python environment.
3. Run the Python script `fraud_detection_anomaly_clustering.py`.
4. The script reads a CSV file (`creditcardcsvpresent.csv`) containing credit card transaction data.
5. Data preprocessing is performed, including renaming columns and removing unnecessary features.
6. Anomaly detection techniques, including Isolation Forest and DBSCAN, are applied to identify fraudulent transactions and outliers.
7. Z-score analysis is conducted to identify outliers based on standard deviations from the mean.
8. Clustering analysis is performed using DBSCAN to group similar transactions together.
9. Decision trees are visualized to aid in interpreting the results of anomaly detection and clustering.

## Results

- Anomaly detection results are presented, including the number of detected outliers and visualizations of decision trees.
- Z-score analysis identifies outliers based on standard deviations from the mean.
- Clustering analysis results in the grouping of similar transactions, enabling the identification of distinct patterns within the data.

## Conclusion

Comprehensive Fraud Detection and Anomaly Clustering offers valuable insights into fraud detection strategies and anomaly identification methods using credit card transaction data. By leveraging anomaly detection algorithms and clustering techniques, financial institutions can enhance security measures and prevent fraudulent activities effectively.

