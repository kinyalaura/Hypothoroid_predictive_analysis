# Predicting Hypothyroid Patients.
![hypothyroid_image](https://www.verywellhealth.com/thmb/DFrZMcT_85wQ87a31NFqigXzH8g=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/overview-of-hypothyroidism-4164534_final-b72106e4545d45afad2caff2910427d9.png)

## Table of Contents:

* Data Set
* Result

## Data Set
This dataset contains hypothyroid observations from numerous patients in a hospital. Observations were drawn from this Hypothyroid dataset. 
There are total of 26 features:

### Categorical Features
* Age: The age of the patient
* Sex: The sex of the patient
* On_Thyroxine: Boolean: (t) True, otherwise (f) False. If the patient is on thyroxine. 
* Query_on_Thyroxine: Boolean: (t) True, otherwise (f) False
* On_antithyroid_medication : Boolean: (t) True, otherwise (f) False. If the patient is on antithyroid medication
* Thyroid_surgery: Boolean: (t) True, otherwise (f) False. If the patient has undergone a thyroid surgery.
* Query_hypothyroid: Boolean: (t) True, otherwise (f) False. If the patient has had hypothoroid before.
* query_hyperthyroid:Boolean: (t) True, otherwise (f) False. If the patient has had hyperthoroid before.
* Pregnant :Boolean: (t) True, otherwise (f) False. If the patient is pregnant.
* Sick: Boolean: (t) True, otherwise (f) False .If the patient is sick
* Tumor: Boolean: (t) True, otherwise (f) False.  If the patient has a tumor. 
* Lithium: Boolean: (t) True, otherwise (f) False. 
* Goitre : Boolean: (t) True, otherwise (f) False. 
* TSH_measured: (t) True, otherwise (f) False.
* T3_measured: (t) True, otherwise (f) False.
* TT4_measured:Boolean:  (t) True, otherwise (f) False.
* T4U_measured: Boolean: (t) True, otherwise (f) False.
* FTI_measured: Boolean: (t) True, otherwise (f) False.
* TBG_measured :Boolean : (t) True, otherwise(f) False.
### Numerical Features
* TSH: The TSH levels.
* T3: T3 levels in the patient
* TT4: TT4 levels 
* T4U : T4U levels 
* FTI: FTI levels 
* TBG: TBG levels
### Target Variable
* Status: The target variable. Does the patient have hypothyroid? (1 = hypothyroid, 0 = negative )

### Result
* Logistic regression accuracy score of 96% and ROC of 0.5 
* Random forests accuracy score of 96%.
* Decision tree adaboost accuracy score of 96%
* Decision Tree gradient boost accuracy score of 96%
* SVM (linear kernel) accuracy score of 45%
* SVM polynomial function accuracy score of 43%
* SVM  Radial basis function (rbf) accuracy score of 95%
* SVM Sigmoid function accuracy score of 94%
