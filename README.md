# supervised-ml-customer-churn
Develop a model to forecast customer turnover at the bank.

--Dataset Summary--
1. Client demographics<br>
   a. Age<br>
   b. Gender<br>
   c. Geography<br>
2. Account information<br>
   a. Balance<br>
   b. Products<br>
   c. Credit Card<br>
   d. Active (Y/N)<br>

--Technique and Process--
1. Downloaded and reviewed data
2. Preprocessed data
3. Exploratory data analysis
![Bank Churn Model Correlation Matrix](sprint_8_eda_image.png)
4. Train different models<br>
   a. Unscaled and scaled data<br>
   b. Upsampled data<br>
   c. Tuning hyperparameters<br>
5. Model validation<br>
   a. F1<br>
   b. AUC-ROC<br>

--Results--
Developed a Random Forest model w/ unscaled, upsampled data and several iterations of hyperparamter tuning that resulted in scores:
1. Validation data<br>
    F1: 61.19<br>
    AUC-ROC: 84.70<br>
2. Test data<br>
    F1: 62.15<br>
    AUC-ROC:86.54<br>
