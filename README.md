Credit Card Fraud Detection using ANN and Autoencoders

Overview
This project focuses on detecting fraudulent credit card transactions using Artificial Neural Networks (ANN) and Autoencoders. It leverages advanced machine learning techniques to identify anomalies in transaction data and improve fraud detection accuracy.

Dataset and Preprocessing
The dataset used in this project contains transaction details with various features, including the trans_date_trans_time feature, which has been retained for analysis. Additionally, SMOTE (Synthetic Minority Over-sampling Technique) has been applied to balance the dataset and enhance model performance.


Model Implementation

The project utilizes:
Autoencoder-based anomaly detection for unsupervised learning.
Feedforward ANN for supervised classification.
SMOTE for handling imbalanced data.

File Links

Below are the links to the test and train datasets used in this project:
Dataset File 1(train): https://pictsctr-my.sharepoint.com/:x:/g/personal/i2k221156_ms_pict_edu/ES3IFdyvfNRKvfA-q1Kd6JMBbmOHv65Yl3_hLpTGS-A8xQ?e=yPh1XN
Dataset File 2(test): https://pictsctr-my.sharepoint.com/:x:/g/personal/i2k221156_ms_pict_edu/ESpEkApShA1Gr_vLd5BkFm4BDv8rVmoQYrMdH4amNt9B7w?e=gkbaQB

Requirements

Ensure you have the following dependencies installed before running the project:

pip install numpy pandas scikit-learn tensorflow keras matplotlib seaborn

How to Run the Project

Clone the repository:

git clone https://github.com/rajdeepthakur10/Credit-Card-Fraud_Detection.git

Install required dependencies:

pip install -r requirements.txt

Run the preprocessing and training scripts.

Evaluate the model on test data.

Results

The model demonstrates effective fraud detection capabilities by leveraging autoencoders to identify anomalies and a neural network for classification.

Author

Rajdeep Thakur
