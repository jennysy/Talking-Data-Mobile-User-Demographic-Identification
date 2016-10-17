# Talking Data - Mobile User Demographics Identification

This repository holds multiple models for Talking Data's dataset available via the following link:

https://www.kaggle.com/c/talkingdata-mobile-user-demographics

This is a multiclass classification problem that identifies which of the classes the user belongs to:

* FEMALE - 23
* FEMALE - 24 - 26
* FEMALE - 27 - 28
* FEMALE - 29 - 32
* FEMALE - 33 - 42
* FEMALE - 43+
* MALE - 22
* MALE - 23 - 26
* MALE - 27 - 28
* MALE - 29 - 31
* MALE - 32 - 38
* MALE - 39+

This classification will be based on the user's phone brand, model, app usage, and geolocation. Multilogarithmic loss is used as the metric to evaluate the models. The following algorithms are used:

* Neural Networks
* Logistic Regression