# Credit-card-detection#

This project uses **supervised machine learning** to detect fraudulent credit card transactions from an **imbalanced dataset** of over 284,000 records. The dataset is preprocessed, analyzed, and used to train a **Random Forest classifier**, with performance evaluated using relevant metrics like ROC-AUC and confusion matrix.

---

> Note: Your exact results may vary based on random seed or train-test split.
> <img width="861" height="450" alt="Screenshot 2025-10-05 at 7 29 39 PM" src="https://github.com/user-attachments/assets/0be3a906-c7b0-4efe-a99c-c22b04124439" />


- **Accuracy**: ~99.9% (but misleading due to imbalance)
- **Precision (fraud class)**: ~84%
- **Recall (fraud class)**: ~76%
- **F1-score (fraud class)**: ~80%
- **ROC-AUC**: ~0.97

 <img width="861" height="450" alt="Screenshot 2025-10-05 at 7 29 39 PM" src="https://github.com/user-attachments/files/23835189/Figure_01.pdf"/>
  This project utilizes machine learning, specifically a Random Forest Classifier, to build a Credit Card Fraud Detection system. The core goal is to accurately distinguish between legitimate (Normal) and fraudulent (Fraud) transactions.

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

