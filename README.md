
### Overview

This project involves developing a machine learning model to predict fraudulent transactions for a financial company. The dataset consists of 6,362,620 rows and 10 columns in CSV format. The goal is to create a model that accurately identifies fraudulent transactions while leaving legitimate ones unaffected. Candidates are encouraged to apply various methods for model development, focusing on both statistical analysis and creativity.

The model will be trained on the calibration data and evaluated on validation data, following standard model development procedures. Both fine-tuning and result interpretation are crucial to building an effective fraud detection model.

### Model Selection

We chose **Random Forest** and **Decision Tree** as our models. Despite having similar accuracy, Random Forest was preferred due to its higher precision, which is critical in fraud detection. In such cases, it's more important to correctly identify fraudulent transactions (high precision) than to simply classify transactions as legitimate. Misidentifying legitimate transactions as fraud or missing actual fraud can have significant consequences.

Additionally, this dataset is highly imbalanced (Legit: Fraud :: 99.87:0.13), which makes Random Forest an ideal choice. Random Forest’s ability to create multiple decision trees helps in simplifying the decision-making process, even though it may be time-consuming.

While models like **XGBoost**, **Bagging**, **Artificial Neural Networks (ANN)**, and **Logistic Regression** can achieve high accuracy, they tend to have lower precision and recall for this particular task.

### Implementation

If you're running the project on your local machine, you can download the dataset from Kaggle https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data.
