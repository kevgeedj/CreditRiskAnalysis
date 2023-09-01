# Credit Risk Analysis

## Overview

The purpose of this investigation was to construct machine learning models for projecting the creditworthiness of borrowers. This was accomplished by utilizing a dataset derived from historical lending activities of a peer-to-peer lending service firm. A key challenge faced was addressing the imbalanced distribution within the data, where healthy loans were notably more abundant compared to risky loans.

The dataset encompassed financial data linked to loans, with the primary objective of determining if a loan should be categorized as high-risk or healthy. Although the specific predictive variables weren't explicitly outlined, it's plausible that they encompassed a variety of financial and borrower-centric attributes.

The stages within the machine learning process encompassed data preprocessing, model training, and evaluation. Addressing the data's inherent imbalance required the application of specialized techniques such as resampling methods to manage the skewed class distribution.

## Results

Machine Learning Model 1:

- Accuracy: 95%
- Precision: 85% for high-risk loans and 100% for healthy loans
- Recall: 91% for high-risk loans and 99% for healthy loans

Machine Learning Model 2:

- Accuracy: 99%
- Precision: 84% for high-risk loans and 100% for healthy loans
- Recall: 99% for both high-risk loans and healthy loans

## Summary

Both Machine Learning Model 1 and Model 2 attained notable accuracy scores, with Model 2 exhibiting a slight improvement at 99%. In regard to precision, Model 1 demonstrated 85% precision for high-risk loans and perfect 100% precision for healthy loans, whereas Model 2 displayed 84% precision for high-risk loans and 100% precision for healthy loans.

Concerning recall, both models achieved an impressive recall rate of 99% for both high-risk loans and healthy loans. This signifies that both models effectively identified the majority of high-risk loans and healthy loans accurately.

Considering these outcomes, it appears that Model 2 outperformed slightly in terms of accuracy and precision for high-risk loans. Nonetheless, both models achieved remarkable recall performance.