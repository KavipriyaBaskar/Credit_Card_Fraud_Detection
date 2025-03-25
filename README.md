# CREDIT CARD FRAUD DETECTION ANALYSIS

## Objective

The objective of this dataset is to build a robust model capable of detecting fraudulent credit card transactions. Credit card fraud is a significant financial crime that results in substantial monetary losses for financial institutions and consumers. Identifying fraudulent transactions accurately while minimizing false positives is crucial to maintaining trust and financial security.
### Dataset Overview:

### Dataset Overview:

- **Columns:**
  - `id`: Unique identifier for each transaction.
  - `V1` to `V28`: Transformed features likely derived from PCA.
  - `Amount`: Transaction amount.
  - `Class`: Target variable where 0 indicates non-fraud and 1 indicates fraud.

- **Summary Statistics:**
  - Total Transactions: 568.63K
  - Total Transaction Amount: 6.85bn
  - Genuine Transactions: 250.27K (3.41bn)
  - Fraudulent Transactions: 208.88K (2.5bn)

- **Transaction Analysis:**
  - High Amount Transactions (> 16,000): 24K
  - Medium Amount Transactions (<=16,000): 190K
  - Low Amount Transactions (< 8,000): 188K

### Dashboard

The dashboard provides visual insights into key metrics and patterns found in the dataset:

- **Overview:**
  - Offers a snapshot of the entire dataset, highlighting transaction volume, fraud rate, and overall distribution.
  - ![Overview](References/Overview.png)

- **Transaction Analysis:**
  - Breaks down transactions by amount categories (high, medium, low) and reveals distribution trends.
  - ![Transaction Analysis](References/Transaction%20Analysis.png)

- **Value Analysis:**
  - Examines the financial impact by evaluating transaction values and spotting anomalies.
  - ![Value Analysis](References/Value%20Analysis.png)

- **Class Category Analysis:**
  - Highlights the distribution between fraudulent and non-fraudulent transactions.
  - ![Class Category Analysis](References/Class%20Category%20Analysis.png)

- **Summary:**
  - Summarizes key findings, offering a concise view of critical statistics and observations.
  - ![Summary](References/Summary.png)

### Expected Outcomes:

- A high-performing fraud detection model that can help financial institutions mitigate risks.
- Insights into transaction patterns that could improve security policies and fraud prevention strategies.
- A scalable solution suitable for real-time fraud detection.
