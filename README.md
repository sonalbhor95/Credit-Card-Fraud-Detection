# Credit-Card-Fraud-Detection

With the increasing use of credit cards, fraud detection has become a critical challenge in the financial industry. Fraudulent transactions are often rare, making it difficult for machine learning models to learn effectively due to data imbalance. This project leverages Synthetic Minority Over-sampling Techniques (SMOTE) and ADASYN (Adaptive Synthetic Sampling) to address class imbalance and improve the detection of fraudulent transactions. The datasets contain transactions that have 492 frauds out of 284,807 transactions. So the dataset is highly unbalanced, the positive class (frauds) accounts for 0.172% of all transactions.
As the dataset is highly imbalanced, we will be using the f1-score, precision/recall score, or confusion matrix for accuracy measures.

Machine learning models are implemented to score each transaction based on its risk of fraud. The results demonstrate that Random Forest Model, combined with SMOTE and ADASYN, achieves the highest accuracy, making it a reliable approach for fraud detection. Key insights include the importance of balancing the dataset to enhance model performance and the cost-effectiveness of prioritizing high-risk transactions for manual review. 

This project underscores the use of advanced sampling techniques and machine learning for building efficient, scalable, and cost-effective fraud detection systems.
