
# Ensemble Learning and Performance Evaluation

## Practical Assignment 5

### Objective
To implement and compare different ensemble learning techniques using machine learning classification algorithms.

### Dataset
Breast Cancer Wisconsin Diagnostic Dataset (Scikit-learn).

- 569 samples
- 30 numerical features
- Binary classification
- Classes: Malignant and Benign

### Algorithms Implemented

**Base Classifiers**
- Logistic Regression
- Decision Tree
- K-Nearest Neighbours (KNN)
- Support Vector Machine (SVM)

**Ensemble Classifiers**
- Stacking Classifier
- AdaBoost Classifier
- Hard Voting Classifier

### Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn

### Performance Evaluation

| Model | Accuracy |
|---|---:|
| Logistic Regression | 98.25% |
| Decision Tree | 92.11% |
| KNN | 95.61% |
| SVM | 98.25% |
| Stacking | 98.25% |
| AdaBoost | 95.61% |
| Hard Voting | 98.25% |

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Conclusion
Stacking and Hard Voting achieved 98.25% accuracy, matching the best-performing individual classifiers. AdaBoost achieved 95.61% accuracy with high recall. The experiment demonstrates how ensemble learning techniques combine multiple classifiers to improve or maintain predictive performance.

### How to Run
1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Run all cells.
4. Observe the classification reports and performance comparison.

