# credit-risk-classification
Analysis Report
- Purpose
  - The purpose of this analysis is to build a logistic regression model based on historical lending activity to identify the credit worthiness of borrowers.

- Definitions
  - Precison tells us out of all the predictions the model made for a certain class, how many were actually correct?
      - If the model predicts 100 loans as high-risk and 84 of them actually are, precision is equal to 84%.

  - Recall tells us out of all actual instances of a class, how many did the model correctly indentify?
    - If there are 100 actual high-risk loans and the model correctly identifies 94 of them, recall is 94%.

  - F1-Score is a single number that balances the precision and recall.
  -   0.84 precision and 0.94 recall would have an F1-score around 0.89.
 

Conclusion:
The logistic regression model predicts healthy loans extremely well (almost perfectly). It does a very good job identifying high-risk loans, with room to reduce false positives.
If your business priority is minimizing financial risk, this model is highly effective, especially given its recall of 0.94 for high-risk cases.
