
# Credit Card Fraud Detection

This dataset contains transaction data from credit cards used by European cardholders in 2013. The main objective is to distinguish fraudulent transactions from non-fraudulent transactions, providing an opportunity to test and compare various machine learning algorithms.

## Contents

The dataset consists of a single CSV file named "creditcard.csv", which contains the following information:

- "Time": Number of seconds elapsed between this transaction and the first transaction
- "V1" to "V28": Principal components obtained by applying PCA to the original features to protect user identities and sensitive information
- "Amount": Transaction amount
- "Class": Target variable, where 1 represents fraudulent transactions and 0 represents non-fraudulent transactions

## Objective

The objective of this project is to develop a machine learning model that can differentiate fraudulent transactions from non-fraudulent ones. Here, we will be using PyCaret, a low-code machine learning library, to facilitate this process.

## PyCaret

PyCaret is an open-source, low-code machine learning library that simplifies the process of creating, training, and deploying models. It provides a wide range of functionality, including data exploration, preparation, modeling, and evaluation.

## Usage

1. Download the dataset: Visit the [Kaggle dataset page](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and download the "creditcard.csv" file.

2. Install PyCaret: Run the command `pip install pycaret` to install PyCaret on your system.

3. Start a Jupyter Notebook.


Contributing
If you would like to contribute improvements to this dataset or its analyses, feel free to create pull requests or open issues on the GitHub page of the dataset.


