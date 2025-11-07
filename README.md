README:
Project Objective:
Build an end-to-end pipeline that detects anomalies in IoT sensor time-series data to help predict equipment faults or maintenance needs.
Tools & Libraries Used:
Python (Google Colab), pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow/keras.

Dataset:
Synthetic time-series data generated with injected anomalies Which is a CSV file.

Main Steps:
Data loading and cleaning (handled missing values, removed duplicates).
Exploratory Data Analysis – plotted sensor signals, checked distributions.
Feature engineering – created rolling mean, rolling standard deviation, and first difference features.

Feature scaling using StandardScaler.
Implemented two anomaly detection models:
Isolation Forest (unsupervised statistical method).
Autoencoder (deep learning model using reconstruction error).
Compared both models visually and by detection accuracy on the synthetic dataset.
Saved final outputs and plots to CSV/PDF.

Results Summary:
Both algorithms successfully detected the injected anomalies.
Isolation Forest: fast, simple, effective for clear outliers.
Autoencoder: better for complex, non-linear patterns.

Output Files:

anomaly_results.csv – final results with anomaly flags.

How to Run:
Open notebook in Google Colab.
Run all cells sequentially.
Use files.Download ("anomaly_results.csv") to download results.

Author:
THARANESH P,
CREATED AT 07-11-2025
