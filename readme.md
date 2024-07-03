# Credit Card Fraud Detection

This repository contains code to detect fraudulent credit card transactions using machine learning techniques, specifically employing a Random Forest classifier. The dataset used is highly imbalanced, where fraudulent transactions are significantly fewer than valid ones.

## Dataset

The dataset used (`creditcard.csv`) contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

### Dataset Features

- **Time**: Seconds elapsed between each transaction and the first transaction in the dataset.
- **Amount**: Transaction amount.
- **Class**: 1 for fraudulent transactions, 0 otherwise.

## Libraries Used

- `numpy`: For numerical operations.
- `pandas`: For data manipulation and analysis.
- `matplotlib` and `seaborn`: For data visualization.
- `sklearn`: For machine learning algorithms and evaluation metrics.

## Workflow

1. **Data Loading and Exploration**:
   - Loading the dataset (`creditcard.csv`) and understanding its structure.
   - Exploring basic statistics and information about the dataset.
   - Visualizing the class distribution and transaction amounts.

2. **Data Preprocessing**:
   - Splitting the data into features (`X`) and target (`Y`).
   - Dividing the dataset into training and testing sets.

3. **Model Training**:
   - Using a Random Forest classifier to train the model.
   - Making predictions on the test set.

4. **Model Evaluation**:
   - Calculating various metrics such as accuracy, precision, recall, F1-score, and Matthews correlation coefficient.
   - Constructing and visualizing the confusion matrix.

5. **Results**:
   - Analyzing the performance of the Random Forest classifier in detecting fraudulent transactions.
   - Discussing potential improvements or further steps, especially given the highly imbalanced nature of the dataset.

## Instructions

To run the code:

1. Clone this repository:

   ```
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   ```

2. Navigate to the project directory:

   ```
   cd credit-card-fraud-detection
   ```

3. Ensure you have the necessary libraries installed (numpy, pandas, matplotlib, seaborn, sklearn).

4. Upload `creditcard.csv` to the same directory or update the file path in the code (`data = pd.read_csv("creditcard.csv")`).

5. Run the Jupyter Notebook or Python script to execute the code.


## Acknowledgments

- Dataset source: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Inspiration and guidance: OpenAI ChatGPT

---
