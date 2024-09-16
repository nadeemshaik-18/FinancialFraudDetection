# FinancialFraudDetection
This project showcases a collection of SQL queries designed to detect and analyze fraudulent transactions in a financial database. The queries utilize various techniques, including recursive Common Table Expressions (CTEs), to identify suspicious patterns and activities
# Queries Included

Detecting Recursive Fraudulent Transactions: Identifies potential money laundering chains where money is transferred from one account to another across multiple steps, with all transactions flagged as fraudulent.

Analyzing Fraudulent Activity over Time: Calculates the rolling sum of fraudulent transactions for each account over the last 5 steps, helping to understand the temporal distribution of fraudulent activities.

Complex Fraud Detection Using Multiple CTEs: Identifies accounts with suspicious activity, including large transfers, consecutive transactions without balance change, and flagged transactions.

Balance Validation: Checks if the computed new updated balance matches the actual new balance in the table, returning rows where they are equal.

Detect Transactions with Zero Balance: Finds transactions where the destination account had a zero balance before or after the transaction.
