Cancer Imbalanced Data Analysis and Prediction


In the context of cancer data analysis and prediction, addressing imbalanced datasets involves a comprehensive approach that encompasses data exploration, preprocessing, model adjustment, and evaluation

Modeling with Imbalanced Data: Instructions on splitting data into training and testing sets, followed by the application of a logistic regression model without considering class weights to establish a baseline performance.

Correcting Imbalance Techniques: Exploration of methods such as adjusting class weights, oversampling with SMOTE, undersampling with NearMiss, and a hybrid approach combining oversampling and undersampling, to improve model performance.

Model Evaluation: Detailed comparison of each approach using confusion matrices and classification reports to assess the effectiveness of each imbalance correction technique.
Conclusion and Recommendations: In analysis of various techniques to address the challenge of an imbalanced dataset in cancer prediction, determined that SMOTEENN, a hybrid method combining Oversampling and Undersampling, outperforms other approaches such as SMOTE (Oversampling) and NearMiss (Undersampling). This conclusion is supported by its superior performance metrics, including a higher True Positive Rate (0.896110) and True Negative Rate (0.865385), as seen in the confusion matrix. Particularly important in the context of cancer dataset analysis is the Recall metric, which reflects the model's ability to correctly identify positive instances of cancer. SMOTEENN achieves balanced and high Recall values (0.90 for class -1 and 0.87 for class 1), outshining the other methods and ensuring a high true positive rate for both negative and positive instances of cancer. 

