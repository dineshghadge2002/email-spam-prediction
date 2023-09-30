# Spam Email Classification

This repository contains code for a spam email classification project. The goal of this project is to build a machine learning model to classify emails as spam or non-spam based on various features extracted from the emails.

## Dataset

The dataset used in this project (`spam_email_dataset.csv`) contains the following columns:

- `Attachments`: Number of email attachments.
- `Link Count`: Number of links in the email.
- `Word Count`: Total number of words in the email.
- `Uppercase Count`: Number of uppercase letters in the email.
- `Exclamation Count`: Number of exclamation marks in the email.
- `Question Count`: Number of question marks in the email.
- `Dollar Count`: Number of dollar signs in the email.
- `Punctuation Count`: Total count of punctuation marks in the email.
- `HTML Tags Count`: Number of HTML tags in the email.
- `Spam Indicator`: Binary label indicating whether the email is spam (1) or not (0).

## Workflow

1. Data Exploration: Analyzing the dataset to understand its structure and characteristics.
2. Data Preprocessing: Selecting relevant columns and preparing the data for model training.
3. Data Visualization: Visualizing data distributions and correlations.
4. Model Training: Building a Random Forest Classifier to predict email spam.
5. Model Evaluation: Calculating accuracy, precision, recall, and F1 score for model performance.

## Usage

1. Clone this repository to your local machine.
2. Install the required libraries.
3. Run the code in a Jupyter Notebook or Python environment.

