# Churn_Detection_Data_Analysis
The objective of this project is to work with a customer dataset from a TV and broadband telecommunications company to build a model to predict future churn.

Insights Include:

![image](https://github.com/user-attachments/assets/a68161bc-155e-48af-8943-bbd295e1e077)
![image](https://github.com/user-attachments/assets/11ac8a9f-43d9-41b8-b133-b6d3a231ede3)


#### KNN Confusion Matrix

Of the ~175 customers that churned (lower two boxes), the model predicted ~50 of them to churn. (predicted correctly)

Of the ~265 customers that did not churn (upper two boxes), the model predicted ~240 of them to not churn. (predicted correctly)

Therefore, this model is very good at predicting non-churning, but rather poor at predicting churning.

#### Decision Tree Confusion Matrix

Of the ~175 customers that churned (lower two boxes), the model predicted ~110 of them to churn. (predicted correctly)

Of the ~265 customers that did not churn (upper two boxes), the model predicted ~210 of them to not churn. (predicted correctly)

Therefore, this model is very good at predicting churning, and good at predicting non-churning.

#### Direct Comparison

The KNN model predicts non-churning more accurately (~240 correct predictions/true negatives compared to DT's ~210).

The DT model predicts churning much more accurately (~110 correct predictions/true positives compared to KNN's ~50)
