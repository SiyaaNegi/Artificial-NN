Bank Customer Churn Prediction using Artificial Neural Networks (ANN)
This project focuses on predicting whether a bank customer will churn (i.e., leave the bank) based on various customer attributes using an Artificial Neural Network (ANN) built with TensorFlow and Keras.

🚀 Project Overview
Input Data: Customer demographic and account information (from CSV file).

Objective: Predict binary output – whether the customer will churn or not.

Approach:

Data Preprocessing: Label Encoding & One Hot Encoding for categorical variables.

Feature Scaling: Standardizing features to improve model performance.

ANN Model: Multi-layer perceptron with two hidden layers.

Training: Model trained over multiple epochs.

Evaluation: Confusion matrix and accuracy score used to assess performance.

🧠 Model Architecture
Input Layer: 11 features (after encoding).

Hidden Layers:

1st Hidden Layer: 6 neurons, ReLU activation.

2nd Hidden Layer: 6 neurons, ReLU activation.

Output Layer: 1 neuron, Sigmoid activation (for binary classification).

🛠️ Technologies & Libraries Used
Python 3.x

NumPy

Pandas

Scikit-learn (Label Encoding, One Hot Encoding, Train-Test Split, StandardScaler)

TensorFlow & Keras (for ANN)

Matplotlib (optional, for visualization)

📊 Dataset Information
The dataset contains customer information such as:

Geography

Gender

Age

Tenure

Balance

Number of Products

Credit Score

Estimated Salary
