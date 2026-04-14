# Breast Cancer Detection using Logistic Regression

## Project Overview

This project implements Logistic Regression to classify whether a tumor is malignant (cancerous) or benign (non-cancerous) using the Breast Cancer dataset.

---

## Objective

* Build a binary classification model
* Predict cancer diagnosis based on medical features
* Evaluate model using classification metrics

---

## Tools & Technologies

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

## Dataset

* Dataset: Breast Cancer Dataset
* Target Variable:

  * diagnosis (M = Malignant, B = Benign)
* Features:

  * Various medical measurements like radius, texture, area, etc.

---

## Steps Performed

1. Imported required libraries
2. Loaded dataset using Pandas
3. Removed unnecessary columns (id, Unnamed: 32)
4. Converted target variable (M → 1, B → 0)
5. Split data into training and testing sets
6. Standardized features using StandardScaler
7. Trained Logistic Regression model
8. Made predictions on test data
9. Evaluated model using:

   * Confusion Matrix
   * Precision
   * Recall
   * ROC-AUC Score
10. Plotted ROC Curve

---

## Model Performance

Confusion Matrix:

```
[[70  1]
 [ 2 41]]
```

Precision: 0.976
Recall: 0.953
ROC-AUC Score: 0.997

The model shows excellent performance with very high accuracy and minimal errors.

---

## ROC Curve

The ROC curve is close to the top-left corner, indicating strong classification capability.

---

## Key Learnings

* Understanding binary classification
* Importance of precision and recall in medical data
* Role of ROC-AUC in evaluating models
* Data preprocessing and feature scaling

---

## Limitations

* Model may still miss some positive cases (false negatives)
* Requires proper preprocessing

---

## Future Improvements

* Hyperparameter tuning
* Try advanced models (Random Forest, XGBoost)
* Improve recall for critical cases

---

## How to Run

1. Install dependencies:

```
pip install pandas scikit-learn matplotlib
```

2. Run the script:

```
python task4.py
```

---

## Conclusion

This project demonstrates how Logistic Regression can be applied to real-world medical data for accurate classification and prediction.

---

## Author

Vasu Jain
