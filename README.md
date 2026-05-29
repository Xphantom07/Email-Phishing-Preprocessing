# Email Phishing Detection – Data Preprocessing

## Overview

This project demonstrates the preprocessing of an Email Phishing Detection dataset to prepare it for Machine Learning models using Python and Scikit-learn.

## Dataset Files

### Before Preprocessing

**File:** `original_dataset.csv`

Features:

* email_id
* sender_email
* subject
* has_link
* has_attachment
* urgency_score
* spelling_errors
* email_length_words
* is_phishing

### After Preprocessing

**File:** `processed_email_dataset.csv`

Changes:

* Extracted **Domain** and **Extension** from sender_email
* Removed `email_id` and `sender_email`
* One-Hot Encoded:

  * subject
  * Domain
  * Extension
* Standardized:

  * urgency_score
  * spelling_errors
  * email_length_words

The final dataset contains only numerical features ready for Machine Learning.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Seaborn
* Jupyter Notebook

## Learning Outcomes

* Data Cleaning
* Feature Engineering
* One-Hot Encoding
* Feature Scaling
* Correlation Analysis
* Machine Learning Data Preparation

## Files Included

* `email_phishing_preprocessing.ipynb`
* `original_dataset.csv`
* `processed_email_dataset.csv`
* `README.md`

## Author

**Bhavik Vavadiya**
