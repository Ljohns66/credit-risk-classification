# credit-risk-classification

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.


Analysis Overview:
The purpose of the analysis was to predict Healthy vs Risky loan performance from a provided data set.

**The results: ** 

                              precision    recall  f1-score   support

           Healthy Loans         1.00      1.00      1.00     18759
           High Risk Loans       0.87      0.89      0.88       625

                 accuracy                           0.99     19384
                macro avg       0.94      0.94      0.94     19384
             weighted avg       0.99      0.99      0.99     19384

* The healthy loan scores were amazing and the high risk loans were also decently high! 
  
* Precision Score - showed much higher for Healthy Loans vs Risky 1.00/0.87 respectively.
* Recall Score - same as above showing 1.00/0.89.
* F1 Score can also be noted - 1.00/0.88.

I would use recommend using the model. The percision got 87% of the high risk predicted correclty as high risk, while Healthy loans was perfect. The recall was strong showing 89% of actual high risks loans identified. It does a good job on both predictions, but it's better at predicting Healthy loans. This makes sense given there's a much larger population of "healthy Loans" with 18765 instances vs only 619 High risk. You should consider there is a chance of 13% of the model missing a high risk loan. So the company using this model would have to consider the risk here.


