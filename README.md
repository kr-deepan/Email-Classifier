# Spam vs Ham Email Classifier

## Project Description

This project involves creating a spam email classifier using machine learning techniques. The model is trained on a labeled dataset of emails, classified as either 'spam' or 'ham'. It uses the Logistic Regression algorithm to predict whether an email is spam or ham based on its content.

## Dataset

The dataset used in this project is `mail_data.csv`, which contains email messages classified as either **spam** or **ham** (non-spam). This dataset is typically used for spam detection, and it is divided into two columns:

- **Category**: The label of the email, which is either 'spam' (0) or 'ham' (1).
- **Message**: The content of the email message, which is a free-text string.

The dataset consists of 5572 rows and 2 columns:
- 4,000+ ham messages (non-spam).
- 1,500+ spam messages.

The dataset is cleaned and preprocessed for model training, where missing values (if any) are handled, and a new `Class` column is added to represent the binary classification (1 for ham, 0 for spam).

## Requirements

To run this project, you need to install the following libraries:

- `numpy`
- `pandas`
- `scikit-learn`

You can install these dependencies using `pip`:

```bash
pip install numpy pandas scikit-learn
