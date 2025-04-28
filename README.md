# German Credit Risk Prediction

This repository contains the implementation of a machine learning model for predicting credit risk using the German Credit dataset. The dataset consists of various attributes such as age, sex, job, credit history, and more to predict whether a person has a good or bad credit risk.

## Dataset

The dataset used in this project is the [German Credit Data](https://archive.ics.uci.edu/ml/datasets/Statlog+(German+Credit+Data)), which contains 1,000 observations with 20 features. The target variable is a binary classification where the output indicates whether a person has good or bad credit risk.

### Features:
- `Age`: Age of the applicant
- `Sex`: Sex of the applicant
- `Job`: Type of job the applicant holds
- `Credit history`: Whether the applicant has a credit history
- `Purpose`: Purpose of the credit
- `Balance`: Current balance in the applicant's checking account
- etc.

## Project Description

This project aims to build a machine learning model to predict whether a given individual will have good or bad credit. The project involves the following steps:
1. **Data Preprocessing**: Cleaning the data, handling missing values, and encoding categorical features.
2. **Exploratory Data Analysis (EDA)**: Analyzing the data distribution, correlations, and feature importance.
3. **Model Training**: Building and training machine learning models such as Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
4. **Evaluation**: Evaluating the performance of the model using metrics such as accuracy, precision, recall, and F1-score.

## Installation

To run this project on your local machine, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/ovttiras/German-Credit-Risk.git
    cd German-Credit-Risk
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

After setting up the environment, you can run the following scripts:

1. **Data Preprocessing and EDA**:
    ```bash
    python preprocess_data.py
    ```

2. **Model Training**:
    ```bash
    python train_model.py
    ```

3. **Model Evaluation**:
    ```bash
    python evaluate_model.py
    ```

## Results

The results of this project are evaluated based on the following metrics:
- Accuracy
- Precision
- Recall
- F1-score

The final model can predict whether an applicant has a good or bad credit risk with a high degree of accuracy.

## Contributing

Feel free to fork the repository, make changes, and submit pull requests. All contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Statlog+(German+Credit+Data)) for providing the German Credit dataset.
- [Scikit-learn](https://scikit-learn.org/) for providing machine learning tools and algorithms.

