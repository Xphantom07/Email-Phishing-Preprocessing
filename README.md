# Email Phishing Detection – Data Preprocessing

## Overview

This project demonstrates the preprocessing of an Email Phishing Detection dataset to prepare it for Machine Learning models using Python and Scikit-learn.

## Dataset (Before Preprocessing)

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

## Preprocessing Performed

* Inspected and explored the dataset
* Extracted **Domain** and **Extension** from sender_email
* Removed unnecessary columns (`email_id`, `sender_email`)
* Applied **One-Hot Encoding** to:

  * subject
  * Domain
  * Extension
* Applied **Standardization** to:

  * urgency_score
  * spelling_errors
  * email_length_words
* Performed correlation analysis

## Dataset (After Preprocessing)

The final dataset contains only numerical features, including:

* Binary features (has_link, has_attachment)
* Standardized numerical features
* One-hot encoded subject, domain, and extension features
* Target column: is_phishing

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

## Author

**Bhavik Vavadiya**
