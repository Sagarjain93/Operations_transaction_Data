**Fraud Detection EDA**

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/4ac9ef16-070c-4906-a89b-f3c50c3e1cdb" />

**Project Overview**

This project explores a financial transactions dataset to identify patterns of fraudulent activity. The dataset includes transactional, network, and user-related features such as transaction details, account IDs, amounts, status, fraud flags, geolocation, device information, network performance, and pin codes. The goal of this EDA is to uncover hidden insights and build a strong foundation for fraud detection models.

**Dataset Information**

The dataset contains the following key columns:

1. transaction_id – Unique ID for each transaction

2. sender_account_id / receiver_account_id – Account identifiers

3. transaction_amount – Value of the transaction

4. transaction_type – Deposit, Transfer, Withdrawal

5. timestamp – Transaction date and time

6. transaction_status – Success or Failure

7. Fraud_flag – Indicator of fraudulent activity (1 = Fraud, 0 = Legitimate)

8. geolocation – Location of transaction

9. device_used – Device used for transaction

10. Network_slice_id – Network category (e.g., Slice1, Slice2, Slice3)

11. latencyms – Network latency in milliseconds

12. bandwidthmbps – Network bandwidth in Mbps

13. pin_code – Regional identifier

**Key Insights from EDA**

*  Fraudulent transactions are not limited to high-value amounts, making rule-based detection unreliable.

*  Latency is slightly higher in failed transactions, but success/failure overlap shows other factors are at play.

*  Correlation heatmap shows weak relationships between numerical variables, meaning fraud cannot be explained by simple linear correlations.

*  Pairplots reveal heavy overlap between fraud and non-fraud cases, confirming the need for multi-dimensional analysis.

*  Geolocation, device usage, and pin codes suggest fraud is context-dependent and linked to behavioral anomalies.

**Overall Conclusion**

Fraudulent activity is subtle and hidden within normal patterns, requiring advanced approaches such as machine learning, feature engineering, and behavioral analysis for effective detection. Simple thresholds (e.g., on amount or latency) are insufficient. Combining transactional, network, and contextual features will help businesses improve fraud prevention, minimize losses, and enhance customer trust.

✨ Author: Sagar Jain
📅 Project Type: Exploratory Data Analysis (EDA)
📂 Domain: Fraud Detection / FinTech

