# Logistic Regression

Logistic Regression (also called Logit Regression) is commonly used to estimate the probability that an instance belongs to a particular class (e.g., what is the probability that this email is spam?).

![download](https://user-images.githubusercontent.com/44503223/127791357-2d1aa4d4-44c8-4e72-a8aa-fba5cc6838ec.png)

#### Content Includes:
- Regularization
  - Just like the other linear models, Logistic Regression models can be regularized using ℓ1 or ℓ2 penalties. Scikit-Learn actually adds an ℓ2 penalty by default.
- Softmax Regression/Multinomial Logistic Regression
  - Whereas binary classifiers distinguish between two classes, multiclass classifiers (also called multinomial classifiers) can distinguish between more than two classes.
  - The Logistic Regression model can be generalized to support multiple classes directly, without having to train and combine multiple binary classifiers. This is called Softmax Regression, or Multinomial Logistic Regression.

## Learn More

For more information, please check out the [Project Portfolio](https://tingting0618.github.io).

## Reference

This repo is my learning journal following:
- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition, by Aurélien Géron (O’Reilly). Copyright 2019 Kiwisoft S.A.S., 978-1-492-03264-9.
