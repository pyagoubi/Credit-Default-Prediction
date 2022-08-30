# Credit Default Prediction

Competition [Link](https://www.kaggle.com/competitions/amex-default-prediction)

<b>Objective  </b>

The objective of this competition is to predict the probability that a customer does not pay back their credit card balance amount in the future based on their monthly customer profile. The target binary variable is calculated by observing 18 months performance window after the latest credit card statement, and if the customer does not pay due amount in 120 days after their latest statement date it is considered a default event.

As submission an ensemble of a XGB model and a LGBM model was used, scoring in the upper 16%.

<b>Explorative Data Analysis  </b>
* Comprehensive EDA: **[Link](https://github.com/pyagoubi/Credit-Default-Prediction/blob/main/Amex_EDA.ipynb)**
* Time series **[Link]()**

<b>Feature Engineering, Training, Validation, Prediction </b>
+ XGB model: **[Link](https://github.com/pyagoubi/Credit-Default-Prediction/blob/main/Amex_XGBoost.ipynb)** 
+ LGB model: **[Link](https://github.com/pyagoubi/Credit-Default-Prediction/blob/main/Amex_LGBM.ipynb)**
