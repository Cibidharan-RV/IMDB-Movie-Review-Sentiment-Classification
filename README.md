# IMDB Movie Review Sentiment Classification

## Overview

* **Dataset**: [IMDB Dataset for 50,000 reviews, balanced dataset](https://docs.google.com/spreadsheets/d/1f6J3OKZEKWR0x69n9OvgaXtjq-pyR4Mif1_5ad_1mzU/edit?usp=sharing)
* **Task**: Binary classification (positive or negative review)
* **Approach**:
    1.  Data processing (removed html tags, punctuation, non-alphabet characters, stopwords)
    2.  Feature extraction using TF-IDF
    3.  Training the model with Logistic Regression
    4.  Evaluation based on accuracy, precision, recall, F1-score and confusion matrix

***

## Dependencies

* **Python Libraries**:
    * `pandas`
    * `scikit-learn`
    * `nltk`
    * `re`

***

## Results

* **Accuracy**: 0.89

| Class    | Precision | Recall |
| :------- | :-------- | :----- |
| Negative | 0.90      | 0.88   |
| Positive | 0.88      | 0.90   |
