# Anomaly Detection in Transaction Data
This project demonstrates anomaly detection in transaction data using a combination of statistical methods and machine learning models. Specifically, it utilizes the Isolation Forest algorithm and a mean + 2*standard deviation threshold for detecting anomalous transaction amounts. The system aims to identify fraudulent or unusual transactions based on features such as transaction amount, account type, and other relevant characteristics.

## Features

**Data Visualizations**:

Distribution of transaction amounts using histograms.

Transaction amount by account type through box plots.

Average transaction amount vs age using scatter plots.

Transaction count by day of the week with bar charts.

**Anomaly Detection:**

**Statistical method:**
Anomalies are detected using a simple threshold (mean + 2 * standard deviation) for transaction amounts.

**Machine Learning method:**

Anomalies are further detected using the Isolation Forest algorithm, which is a robust method for identifying outliers in high-dimensional datasets.

**Classification Report:**

A classification report is generated to evaluate the performance of the anomaly detection model.

**User Input:**

Users can input transaction data to predict if the transaction is normal or anomalous.
