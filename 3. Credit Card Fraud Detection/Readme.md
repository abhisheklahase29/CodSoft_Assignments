


# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. It utilizes a dataset containing credit card transactions, including both legitimate and fraudulent ones, to train a model to classify transactions as either fraudulent or legitimate.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud) and contains transactions made by credit cards in September 2013 by European cardholders. It consists of numerical features obtained through a PCA transformation due to privacy concerns. The target variable is 'Class', where 1 indicates a fraudulent transaction and 0 indicates a legitimate transaction. 

## Analysis

- The dataset is highly imbalanced, with a significantly smaller number of fraudulent transactions compared to legitimate ones.
- Exploratory data analysis (EDA) reveals differences in transaction amounts between legitimate and fraudulent transactions.
- Correlation analysis helps identify features that may be relevant for fraud detection.

## Preprocessing

- Sampling techniques are used to balance the dataset by randomly selecting a subset of legitimate transactions.
- The 'Time' column is transformed into a new feature representing the hour of the day to capture any time-related patterns.
- The dataset is split into training and testing sets.

## Model Training

- Logistic Regression is chosen as the classification algorithm due to its simplicity and effectiveness in binary classification tasks.
- The model is trained on the balanced dataset.
- Performance metrics such as accuracy, precision, recall, and F1-score are used to evaluate the model.

## Results

- The trained model achieves decent accuracy in detecting fraudulent transactions.
- Performance metrics indicate a good balance between precision and recall, crucial for fraud detection tasks.
- The model can be further optimized and evaluated using different algorithms and techniques.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Run the `credit_card_fraud_detection.ipynb` notebook or execute the Python script to train the model and evaluate its performance.
4. Experiment with different algorithms, hyperparameters, and preprocessing techniques to improve model performance.

## Dependencies

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Contributors

- [Abhishek Lahase](https://github.com/abhisheklahase29) - Project Lead


