# SafePay#

This project uses **supervised machine learning** to detect fraudulent credit card transactions from an **imbalanced dataset** of over 284,000 records. The dataset is preprocessed, analyzed, and used to train a **Random Forest classifier**, with performance evaluated using relevant metrics like ROC-AUC and confusion matrix.

---

> Note: Your exact results may vary based on random seed or train-test split.
- **Accuracy**: ~99.9% (but misleading due to imbalance)
- **Precision (fraud class)**: ~84%
- **Recall (fraud class)**: ~76%
- **F1-score (fraud class)**: ~80%
- **ROC-AUC**: ~0.97
Key Accomplishments Illustrated by the Confusion Matrix

The confusion matrix provides a comprehensive view of the model's performance on the test data:

High Accuracy on Normal Transactions (True Negatives): The model correctly identified 56,862 transactions as Normal when they were truly Normal. This demonstrates strong performance in handling the majority class.

High Precision/Low False Alarm Rate: Only 2 Normal transactions were incorrectly flagged as Fraud (False Positives). This means that when the model predicts fraud, it is highly reliable.

Effective Fraud Capture (True Positives): The model successfully identified 78 actual fraudulent transactions (True Positives).

Critical Misses (False Negatives): The most crucial area for improvement is the 20 fraudulent transactions that the model failed to detect (False Negatives). Addressing these missed cases is essential to minimize financial losses.


⚠️ This highlights that traditional accuracy is not reliable for imbalanced datasets.

END result- 
<img width="1590" height="1198" alt="image" src="https://github.com/user-attachments/assets/d4ce9979-5125-48aa-9439-1194ee15c1b4" />


---

## 📌 Key Concepts

- Handling **class imbalance** in real-world datasets
- Using **Random Forests** for fraud detection
- Importance of **recall and precision** over accuracy
- Visualizing model performance (ROC curve, confusion matrix)

