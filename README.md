# Mobile Price Range Classifier

This project uses multiple machine learning classifiers to predict the **price range of mobile phones** based on their technical specifications.

---

## Models Used

| Model | Training Accuracy | Testing Accuracy | Observation |
|--------|------------------:|-----------------:|--------------|
| **SVM Classifier** | 0.9522 | 0.9515 | Best overall performance with good generalization |
| **Linear Regression** | 0.9180 | 0.9190 | Used as a baseline model |
| **Decision Tree Classifier** | 0.8216 | 0.7636 | Showed signs of overfitting |
| **Random Forest Classifier** | 0.9686 | 0.8621 | Showed signs of overfitting |
| **XGBoost Classifier** | 1.0 | 0.9121 | Showed signs of overfitting |

---

## Summary

- Among all models tested, the **SVM Classifier** achieved the **highest and most consistent accuracy** across both training and testing datasets.  
- Tree-based models (Decision Tree, Random Forest, XGBoost) exhibited **overfitting**, performing very well on training data but poorly on unseen data.  
- The project highlights the importance of **model evaluation**, **cross-validation**, and **regularization** to ensure better generalization.

---

## Technologies Used

- **Python**
- **Scikit-learn**
- **XGBoost**
- **Pandas**, **NumPy**
---
