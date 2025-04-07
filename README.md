# ELE489-Homework-2

This project was completed as part of the Fundamentals of Machine Learning course. I worked with the Banknote Authentication dataset to explore decision trees and various statistical measures used in image analysis.

## Files
- `analysis.ipynb`: Jupyter Notebook that contains the full implementation, visualizations, and explanations.
- `Obtained_images/`: Folder containing all result images including decision tree visualizations and confusion matrix reports.
- `data_banknote_authentication.txt`: The dataset used for classification.

## Project Overview
The dataset contains 1372 samples with 4 numerical features (variance, skewness, kurtosis, entropy) and a binary class label (0 for fake, 1 for authentic).

Key steps:
- Calculated Gini index manually to understand how decision trees choose the root node.
- Visualized features using a pair plot to examine class separability.
- Trained decision tree models using different hyperparameters (criterion, max depth, min samples split).
- Evaluated performance using classification reports and confusion matrices.
- Visualized decision trees and extracted feature importance scores.

## Notes
This project helped me understand how decision trees make decisions, how hyperparameters affect model interpretability and performance, and how feature statistics relate to image classification. Visualizing the pair plots and decision trees gave valuable insights into the structure of the dataset.
