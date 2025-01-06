# credit-risk-classification
Module 20

This analysis is to use various techniques to train and evaluate a model based on loan risk. I use historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Using the Logistic Regression Model combined with the Confusion Matrix the following was uncovered:

    1.Accuracy was at a 99% hit rate which makes this a very useful model to find the risk of the applicants.

    2. Precision for class 0 clients was at 100% which tells us that it correctly call the risks at all times while class 1 clients only had a 87% correct predictions which is good but maybe not good enough for a client.

    3.Recall, for class 0, the recall is 1.00, meaning all actual 0s were correctly predicted. For class 1, the recall is 0.95, indicating that 95% of the actual 1s were correctly identified.

              precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      0.95      0.91       625

    accuracy                           0.99     19384
   macro avg       0.94      0.97      0.95     19384
weighted avg       0.99      0.99      0.99     19384


It has a much higher rate of success in rating healthy loans vs high risk because of factors maybe not shown in the data. Many factors can determine what could be called high risk, maybe they lost a job recently and started to miss payments, mental health issues, etc.

I can recommend the model to the client as we can train the model for more accurate results.

With 99% accuracy rating for predictions, it can be use to filter out all the risky loans and put more of a focus on the loans that will succeed and be payed back.