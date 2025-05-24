# credit-risk-classification

The purpose of this analysis is to build a machine learning model that can predict the risk level of loans—classifying them as either healthy (0) or high-risk (1)—to help the company make better lending decisions.

📊 Results
Accuracy Score: ~94%

Precision (Healthy Loans - 0): High (model correctly predicts most healthy loans)

Recall (High-Risk Loans - 1): Low (model misses many high-risk loans)

✅ Summary
The logistic regression model performs well for predicting healthy loans but struggles to identify high-risk loans. While it's reliable for screening safe borrowers, it may fail to flag risky applicants. We do not recommend using this model in production without further improvement (e.g., balancing the dataset or using a more complex model), as it may expose the company to financial risk from undetected high-risk loans.

