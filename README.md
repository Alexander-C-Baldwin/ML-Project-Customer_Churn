##### I've noticed some output for code is not appearing in Github. You can copy and paste url into https://nbviewer.org/ to view code output if needed.


# ML-Project-Customer_Churn
Customer Churn Prediction Comparing ML Models

Can we predict and prevent Telco customer churn?



## Business Question:
Churn is when a customer currently using our services leaves our company. This is costly for our business in many various ways. The business best interest is to retain current customers. Is there a machine learning model that can best help us predict potential customer churn? Using the developed model, we can predict customer churn and then develop strategies in order to retain these customers preemptively.


## Key Metrics:
To predict potential customer churn, I have compared 36 machine learning models. These models were compared using four relevant metrics. These metrics are crucial in helping evaluate the accuracy and variance of the model as well as comparing the differences between the models to find the best for predicting customer churn. These metrics include the following.

•	Accuracy Score – This shows the overall accuracy of the model.

•	Recall Score – Shows the true positive churn prediction rate the model performs.

•	R2 Score – Explains how well variables in the model are correlated.

•	Mean Absolute Error – Measure the magnitude of errors in the forecast.


## Analysis Summary & Model Options:
In order to find the best model that can help the business predict potential customer churn I have compared 36 models across the previously defined relevant metrics. This was done by training, testing, and validating each of these models using a dataset detailing Telco customer churn over 7,043 customer accounts and 46 variables. 12 modeling methods were used and tuned 3 times each resulting in 36 models. A summary of the outputs for these models are included in the notebook which can be used for comparison



## Conclusion:
All the classifier models seemed to be pretty consistent throughout with this dataset with top accuracy scores being from 78% to 80.5%. This shows we are able to predict customer churn with machine learning methods. 

Overall, the best model to predict customer churn is the neural network model number 1 (ANN – 1). It proved to be the most accurate model which is the main metric being targeted when comparing. Also, this model performed the best in mean absolute error showing the smallest error among the models. It had the third best recall as well.

Some limitations of this dataset are that it looks at a customer’s current situation and does not look at behaviors for contribution to churn. Such calls with customer service, if they are aware of competitors, satisfaction with service, and other behavioral data may be useful in better predicting customer churn. 

## Recommendations:

### Application:
I recommend that we start applying the neural network number 1 model to our customers data in order to predict customer churn. When we discover a customer that is predicted to churn, we should deploy strategies to retain this customer business and prevent the churn. 

### Customer Retention:
I recommend the next steps to be develop strategies to retain customers when churn is predicted. Some methods could be promotions like special discounts for a period of time. Or upgrading the customers service to a higher tier at a lower price. We could send marketing material along with these discounts thanking the person for being a valued customer. Another strategy, once a client is predicted to churn, our customer service team should get in touch with the client through phone or email in an attempt to figure any underlying issues the client may be having and provide a resolution for these issues. 

### Build Better Models:
Some limitations of this dataset are that it looks at a customer’s current situation and does not look at behaviors for contribution to churn. I recommend gathering this behavioral data in order to build better models that are more accurate in predicting churn among customers.
