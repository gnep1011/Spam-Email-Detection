# Spam-Email-Detection
I build classification models to detect whether an email is spam or not, based on the email characteristic.

In the project, there are two scenarios:

The best model in terms of the overall predictive accuracy.
The best model in terms of the cost sensitive condition.
One model has best accuracy, while the other is a cost sensitive model to minimize misclassification cost.

I built the models using five techniques, decision tree, logistic regression, k-nearest neighbors, support vector machine and LightGBM. I first used nested GridSearchCV to find the best model, then conducted hyper-parameter tuning to find the best outcome of the model.
