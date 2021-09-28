# Featuretools

[Quick Start](https://github.com/dongzhang84/Featuretools/blob/main/get_started.ipynb): follow [this link](https://featuretools.alteryx.com/en/stable/index.html).

[Getting Started](https://github.com/dongzhang84/Featuretools/blob/main/get_started_detailed.ipynb): follow [this tutorial](https://featuretools.alteryx.com/en/stable/getting_started/using_entitysets.html).

[Titanic Problem](https://github.com/dongzhang84/Featuretools/blob/main/Titanic_Featuretools.ipynb): From automatic feature engineering to automatic feature selection, but only for a given test dataset. 

Titanic Automation: [Model Generation with Training Data](https://github.com/dongzhang84/Featuretools/blob/main/Titanic_Featuretools_automation_train.ipynb)
- FeatureTools automatized FE, saved FE
- Convert categorical data to numbers, saved in pickle
- Feature selecion (Remove collinear features), saved in pickle
- Modeling (random forest), saved in pickle

[Model Generation version II](https://github.com/dongzhang84/Featuretools/blob/main/Titanic_automation_train_v2.ipynb): feature selection using Recursive Feature Elimination (RFE) with Random Forest (less accurate than removing collinear features)

[Model Generation version III](https://github.com/dongzhang84/Featuretools/blob/main/Titanic_automation_train_v3.ipynb): feature selection using Recursive Feature Elimination (RFE) with Logistic Regression (even less accurate than RFE with RF)

[Model Prediction with Testing Data](https://github.com/dongzhang84/Featuretools/blob/main/Titanic_Featuretools_automation_test.ipynb)
- Load saved four things mentioned above, and do the prediction

More detailed [FeatureTools Notes](https://github.com/dongzhang84/Study_Notes/blob/main/FeatureTools_Notes.md) based on the Titanic problem. 
