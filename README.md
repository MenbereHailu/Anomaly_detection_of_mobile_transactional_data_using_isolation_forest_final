# Anomaly Detection in Mobile Banking Transactions Using Isolation Forest

## Overview
This study investigates **anomaly detection in mobile banking transactions** using the **Isolation Forest** algorithm, a machine learning model known for efficiently identifying outliers in large datasets. The primary goal is to detect irregular transaction patterns that may indicate **fraudulent activities** or **system malfunctions**.

## Dataset
- **Source:** Mobile banking transactions from a commercial bank  
- **Timeframe:** One week in June 2024  
- **Volume:** 22,890,674 transactions covering 4,298,320 debit accounts  
- **Preprocessing:**  
  - Handled missing values and inconsistencies  
  - Extracted key features to ensure high-quality model inputs

## Features Used
Key features extracted for the Isolation Forest model include:  
- **Total transaction amount** per debit account  
- **Transaction frequency**  
- **Deviations in debit amounts** (mean, max, standard deviation)  
- **Transaction modes/types**  
- **Behavioral patterns** such as unusual sequences or changes in account activity  

These features capture patterns that distinguish normal behavior from anomalies.

## Methodology
- Applied the **Isolation Forest algorithm** to the dataset  
- The model creates an ensemble of decision trees that isolate outliers by recursively partitioning data points  
- Transactions that are quickly isolated across multiple trees are classified as **anomalous**  

## Results
- **Total anomalous accounts detected:** 42,982  
- Accounts identified as anomalous exhibited unusual transaction behaviors, indicating potential **security risks** or **operational issues**  
- Confirms the **robustness of Isolation Forest** in handling high-dimensional, high-volume financial data

## Significance
- Demonstrates the potential of machine learning for **fraud detection in mobile banking systems**  
- Provides a **scalable and effective solution** for anomaly detection in dynamic transaction environments  
- Supports the development of more **secure and resilient financial platforms**

## Conclusion
The Isolation Forest algorithm is effective in detecting irregularities in mobile banking transactions. Its application enhances the security framework of financial systems by providing a data-driven approach to **fraud prevention** and **operational risk mitigation**.
