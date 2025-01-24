# credit-risk-classification
### **Credit Risk Analysis Report**

#### **Overview**

The purpose of this Credit Risk Analysis is to evaluate the performance of a machine learning model in predicting credit risk for loan applicants. Specifically, the model aims to classify loans into two categories: healthy loans (label 0) and high-risk loans (label 1). By identifying high-risk loans, the company can make more informed lending decisions, reduce the likelihood of defaults, and better manage its portfolio. This analysis will assess the model's accuracy, precision, and recall to determine if it is a reliable tool for credit risk evaluation.

#### **Model Evaluation: Accuracy, Precision, and Recall**

- **Accuracy**: 99%  
  The model correctly classifies 99% of all loans, indicating it is highly accurate in its predictions overall.

- **Precision for label 0 (healthy loans)**: 1.00  
  The model is perfect at predicting healthy loans, meaning that when it classifies a loan as healthy, it is almost always correct.

- **Recall for label 0 (healthy loans)**: 1.00  
  The model successfully identifies all healthy loans, with no false negatives for this label.

- **Precision for label 1 (high-risk loans)**: 0.87  
  The model correctly identifies 87% of the high-risk loans it classifies, but it also misidentifies some healthy loans as high-risk.

- **Recall for label 1 (high-risk loans)**: 0.95  
  The model captures 95% of the actual high-risk loans, with only a small percentage of high-risk loans being missed.

#### **Summary of Results**

The machine learning model performs well in classifying both healthy and high-risk loans. It perfectly identifies healthy loans with 100% precision and recall. For high-risk loans, it has a slightly lower precision of 87% but a strong recall of 95%, meaning it captures most high-risk loans, though it occasionally misclassifies healthy loans as high-risk. With an overall accuracy of 99%, the model is highly effective for credit risk evaluation and should be recommended for use by the company. The tradeoff in precision for high-risk loans is acceptable given the model's strong recall.
