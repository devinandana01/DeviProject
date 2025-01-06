# Detecting Online Payment Fraud: A Machine Learning Approach for Predictive Analytics

This project implements a machine learning-based approach to detect fraudulent transactions in online payments. Utilizing the `Financial Dataset` from IEEE Dataport, the project employs data preprocessing, exploratory data analysis, and machine learning techniques to predict and analyze fraudulent activities.

## Features

- Data preprocessing and visualization.
- Handling class imbalance with techniques like SMOTE (Synthetic Minority Oversampling Technique).
- Implementation of multiple machine learning models including:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - XGBoost
- Feature selection and evaluation using metrics such as confusion matrices, ROC curves, and classification reports.
- Extensive data visualization to analyze fraud patterns.

## Dataset

The project uses the `Financial Dataset` provided by IEEE Dataport. It contains a variety of features, including:

- `TRANSACTION_ID`, `TX_AMOUNT`, `TX_TIME_SECONDS`, `TX_FRAUD`
- Derived features such as `Amount_Deviation`, `Amount_Threshold`, and `TX_DURING_WEEKEND`.

The dataset is accessible [here](https://ieee-dataport.org/documents/financial-dataset).

## Requirements

The following Python libraries are required for the project:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- imbalanced-learn

Install the dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/devinandana01/DeviProject.git
   cd DeviProject
   ```

2. Open the Colab Notebook:

   ```bash
   colab notebook Devi_v18.ipynb
   ```

3. Execute the cells sequentially to preprocess the dataset, train models, and evaluate performance.

## Results

- Model performance is evaluated using metrics like accuracy, precision, recall, F1-score, and AUC-ROC.
- Visualizations highlight the distribution of fraudulent transactions and model effectiveness.

## Contributions

Contributions are welcome! Please feel free to submit a pull request or raise an issue.

## License

This project is licensed under the MIT License.

