# Yandex Practicum Data Science Projects
<p align="center">
  <img src="https://github.com/ivan-aleshin/yandex-practicum-projects/blob/main/img/yandex_practicum.png?raw=true" />
</p>

Repository of **Data Analytics, Data Science, Machine Learning** projects completed during the educational courses at **Yandex Practicum**

[![certificate](https://img.shields.io/badge/сertificate-Data%20Scientist%20ENG-A8E4A0)](https://github.com/ivan-aleshin/yandex-practicum-projects/blob/main/certificates/ds_eng.md)  
[![certificate](https://img.shields.io/badge/сertificate-Data%20Scientist%20RUS-A8E4A0)](https://github.com/ivan-aleshin/yandex-practicum-projects/blob/main/certificates/ds_rus.md)  

## Projects list:  
[![PROJ_15](https://img.shields.io/badge/🔗%20Project-15-87CEEB)](#optimization-of-electricity-consumption-in-industry) "Optimization of electricity consumption in industry"  
[![PROJ_13](https://img.shields.io/badge/🔗%20Project-13-87CEEB)](#age-recognition-using-cv-deep-learning-model) "Age Recognition Using CV Deep Learning Model"  
[![PROJ_12](https://img.shields.io/badge/🔗%20Project-12-87CEEB)](#natural-language-processing-toxic-comments-detection-using-ml) "Natural Language Processing: Toxic Comments Detection Using ML"  
[![PROJ_11](https://img.shields.io/badge/🔗%20Project-11-87CEEB)](#number-of-taxi-orders-prediction) "Number of Taxi Orders Prediction"  
[![PROJ_10](https://img.shields.io/badge/🔗%20Project-10-87CEEB)](#car-price-prediction) "Car Price Prediction"  
[![PROJ_09](https://img.shields.io/badge/🔗%20Project-09-87CEEB)](#development-of-personal-data-protection-algorithm) "Development of Personal Data Protection Algorithm"  
[![PROJ_08](https://img.shields.io/badge/🔗%20Project-08-87CEEB)](#prediction-of-enrichment-efficiency-in-the-recovery-of-gold-from-ore) "Prediction of Enrichment Efficiency in the Recovery of Gold from Ore"  
[![PROJ_07](https://img.shields.io/badge/🔗%20Project-07-87CEEB)](#exploration-of-new-oil-fields-regions-using-ml-models) "Exploration of New Oil Fields Regions Using ML Models"  
[![PROJ_06](https://img.shields.io/badge/🔗%20Project-06-87CEEB)](#bank-customer-churn-prediction) "Bank Customer Churn Prediction"  
[![PROJ_05](https://img.shields.io/badge/🔗%20Project-05-87CEEB)](#ml-model-for-mobile-tariff-recommendation) "ML Model for Mobile Tariff Recommendation"   
[![PROJ_04](https://img.shields.io/badge/🔗%20Project-04-87CEEB)](#video-games-markets-research) "Video Games Markets Research"  

***
  

[![PROJ_15](https://img.shields.io/badge/go%20to%20PROJECT-15-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/15_prediction_temperature_of_steel)  
## [Optimization of electricity consumption in industry](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/15_prediction_temperature_of_steel)

### Task
Optimize electricity consumption at the steel plant. Develop ML model for predicting steel temperature.  

### Description
Given data from various indicators of a steel plant.
The task is to develop ML model to predict final temperature of steel with MAE at least 6.8.  

Exploring the available data, it types, missings, duplicates, basic statistics, plot graphs.  
Data was cleaned and preprocessed. Some missings in data was filled some data had to be deleted. 
Then data was aggregated from 7 different tables to the one. 10 new features was generated.
Three different ML models were trained and tuned on cross-validation with feature transformation via pipeline. After determining the best model, we've evaluated the importance of the features. Three ifferent methods was used to explore feature importances. Based on the study of feature importances a new lightweight model was developed with only 10 features (instead of 33) and MAE below 5.4.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)
[![ML Engineer](https://img.shields.io/static/v1?label=Trend&message=ML%20Engineer&color=6495ED)](#)  

**Tools & Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SKLearn](https://img.shields.io/static/v1?label=tool&message=sklearn&color=cd6133)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=matplotlib&color=DE3163)](#)
[![Seaborn](https://img.shields.io/static/v1?label=tool&message=seaborn&color=CCCCFF)](#)  
[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=FFBF00)](#)
[![Data Visualization](https://img.shields.io/static/v1?label=skill&message=Data%20Visualization&color=9FE2BF)](#)  

***

[![PROJ_13](https://img.shields.io/badge/go%20to%20PROJECT-13-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/13_cv_age_recognition)
## [Age Recognition Using CV Deep Learning Model](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/13_cv_age_recognition)

### Task
Develop a CV model to recognise an age of customers by their photo.

### Description
Supermarket chain Bread&Salt introduces a computer vision system for processing customer's photos. Photo fixation at checkout area will help to determine the age of customers in order to:  
- Analyze purchases and offer products that may be of interest to buyers of this age group;
- Control the conscientiousness of cashiers when selling alcohol;
- Security reasons.

Study summary:
THe exploratory analysis was conducted first. There are not many photos were available. Therefore the augumentation was implemented.
The pretrained Resnet-102 neural network model was finetuned for the purpose of stidy. The last two layers of model were replaced, respectively, with a connected layer with one output neuron and leaky ReLU activation. The final value of the MAE metric on the validation sample was 5.91.

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)  

**Tools & Skiils**  
[![Keras](https://img.shields.io/static/v1?label=tool&message=Keras&color=40407a)](#)
[![Tensorflow](https://img.shields.io/static/v1?label=tool&message=Tensorflow&color=cd6133)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![ResNet](https://img.shields.io/static/v1?label=tool&message=ResNet&color=DFFF00)](#)  
[![DL](https://img.shields.io/static/v1?label=skill&message=Deep%20Learning&color=1B9CFC)](#)
[![CV](https://img.shields.io/static/v1?label=skill&message=Computer%20Vision&color=B33771)](#)

***

[![PROJ_12](https://img.shields.io/badge/go%20to%20PROJECT-12-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/12_nlp_toxic_comments_detection)
## [Natural Language Processing: Toxic Comments Detection Using ML](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/12_nlp_toxic_comments_detection)

### Task
Develop NLP model to detect toxic comments.

### Description
Online store "Wikishop" launches a new service. Now users can edit and supplement product descriptions, just like in wiki communities. The store needs a tool to speedup the moderation of product desctiption commentaries by automating their tone assessment. The tool will use an ML model which can detect toxic comments and submit them for moderation.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)
[![ML Engineer](https://img.shields.io/static/v1?label=Trend&message=ML%20Engineer&color=6495ED)](#)  

**Tools & Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SKLearn](https://img.shields.io/static/v1?label=tool&message=sklearn&color=cd6133)](#)
[![Spacy](https://img.shields.io/static/v1?label=tool&message=Spacy&color=cd6133)](#)
[![NLTK](https://img.shields.io/static/v1?label=tool&message=nltk&color=cd6133)](#)
[![TF-IDF](https://img.shields.io/static/v1?label=tool&message=tf-idf&color=cd6133)](#)  
[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![NLP](https://img.shields.io/static/v1?label=skill&message=Natural%20Language%20Processing&color=2ECC71)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=FFBF00)](#)  

***

[![PROJ_11](https://img.shields.io/badge/go%20to%20PROJECT-11-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/blob/main/11_timeseries_prediction/11_timeseries_prediction.ipynb)
## [Number of Taxi Orders Prediction](https://github.com/ivan-aleshin/yandex-practicum-projects/blob/main/11_timeseries_prediction/11_timeseries_prediction.ipynb)

### Task
Train ML model to predict the number of taxi orders for the next hour.  

### Description
The purpose of this study is to develop optimal model for predicting the number of taxi orders in next hour. There are historical data on taxi orders at airports provided. The task were resolved into timeseries prediction.

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)  

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SKLearn](https://img.shields.io/static/v1?label=tool&message=sklearn&color=cd6133)](#)  
[![TS](https://img.shields.io/static/v1?label=skill&message=Timeseries&color=52BE80)](#)
[![Stats](https://img.shields.io/static/v1?label=skill&message=Statistics&color=AF7AC5)](#)
[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=FFBF00)](#)
[![Data Visualization](https://img.shields.io/static/v1?label=skill&message=Data%20Visualization&color=9FE2BF)](#)  

***

[![PROJ_10](https://img.shields.io/badge/go%20to%20PROJECT-10-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/10_car_price_prediction)
## [Car Price Prediction](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/10_car_price_prediction)

### Task
Train the model to determine the market value of the car based on its parametres  

### Description
A company selling used cars is developing an app. One of the features attracting new clients is functionality of estimating a car's worth based on its features and characteristics. A car cost forcasting model was created using historical data.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)
[![Data Analyst](https://img.shields.io/static/v1?label=Trend&message=Data%20Analyst&color=FF7F50)](#)  

**Tools & Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SKLearn](https://img.shields.io/static/v1?label=tool&message=sklearn&color=cd6133)](#)  
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=FFBF00)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Data Visualization](https://img.shields.io/static/v1?label=skill&message=Data%20Visualization&color=9FE2BF)](#)  

***

[![PROJ_09](https://img.shields.io/badge/go%20to%20PROJECT-09-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/09_personal_data_protection_method)
## [Development of Personal Data Protection Algorithm](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/09_personal_data_protection_method)

### Task
Develop a method to transform data for the insurance company clients personal information protection.  

### Description
An insurance company needs to protect its customers information using data transformation methods. This helps to prevent sensitive data from being decrypted. This project required data preprocessing. The linear regression model algorythm was validated by multiplying the results on an invertible matrix. Conversely, multiplication on an inverse matrix of the invertible matrix proved the model works correctly. R2 score for linear regression model was measured on indentical data: initial data first, then data multiplied on invertible matrix (size of the features count). Metrics matched perfectly which means the algorythm works.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)
[![ML Engineer](https://img.shields.io/static/v1?label=Trend&message=ML%20Engineer&color=6495ED)](#)

**Tools & Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SKLearn](https://img.shields.io/static/v1?label=tool&message=sklearn&color=cd6133)](#)
[![Numpy](https://img.shields.io/static/v1?label=tool&message=numpy&color=F7DC6F)](#)  
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=FFBF00)](#)
[![Linear Algebra](https://img.shields.io/static/v1?label=skill&message=Linear%20Algebra&color=B33771)](#)
[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![OOP](https://img.shields.io/static/v1?label=skill&message=OOP&color=58D68D)](#)  

***

[![PROJ_08](https://img.shields.io/badge/go%20to%20PROJECT-08-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/08_ml_in_metall_industry)
## [Prediction of Enrichment Efficiency in the Recovery of Gold from Ore](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/08_ml_in_metall_industry)

### Task
Develop ML model to predict recovery rate for gold from gold ore  

### Description
A gold mining company needs a solution to perfect its efficiency. A model forecasting gold recovery rate is created using ore extraction and refinement parametres data. The model is developed to help optimize production by assessing ore quality to avoid financial losses on ineffective operations.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)
[![Data Analyst](https://img.shields.io/static/v1?label=Trend&message=Data%20Analyst&color=FF7F50)](#)
[![ML Engineer](https://img.shields.io/static/v1?label=Trend&message=ML%20Engineer&color=6495ED)](#)  

**Tools & Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SKLearn](https://img.shields.io/static/v1?label=tool&message=sklearn&color=cd6133)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=matplotlib&color=DE3163)](#)
[![Seaborn](https://img.shields.io/static/v1?label=tool&message=seaborn&color=CCCCFF)](#)  
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=FFBF00)](#)
[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Custom Metrics](https://img.shields.io/static/v1?label=skill&message=Custom%20Metrics&color=BB8FCE)](#)
[![Data Visualization](https://img.shields.io/static/v1?label=skill&message=Data%20Visualization&color=9FE2BF)](#)  


***

[![PROJ_07](https://img.shields.io/badge/go%20to%20PROJECT-07-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/07_ml_oil_fields_prediction)
## [Exploration of New Oil Fields Regions Using ML Models](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/07_ml_oil_fields_prediction)

### Task
Selecting the most profitable regions for oil extraction. Develop ML model to determine the area where drilling will be the most profitable with the least risk of loss.  

### Description
An oil company needs to make decion on developing the next well location. The existing data is oil samples' characteristics for varoius wells. Data contains oil quality parametres and oil reserves information in three regions. Characteristics of each well in the region are already known.
A machine learning model forecasts oil reserves in new wells. The model assists in picking the region with most profitable set of wells to be drilled.
Part of the research is potential profit and risk assessment using Bootstrap methodology.  

**Trend**  
[![Data Analyst](https://img.shields.io/static/v1?label=Trend&message=Data%20Analyst&color=FF7F50)](#)
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)
[![ML Engineer](https://img.shields.io/static/v1?label=Trend&message=ML%20Engineer&color=6495ED)](#)  

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SKLearn](https://img.shields.io/static/v1?label=tool&message=sklearn&color=cd6133)](#)  
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=FFBF00)](#)
[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Bootstrap](https://img.shields.io/static/v1?label=skill&message=Bootstrap&color=B33771)](#)  

***

[![PROJ_06](https://img.shields.io/badge/go%20to%20PROJECT-06-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/06_bank_churn_prediction)
## [Bank Customer Churn Prediction](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/06_bank_churn_prediction)

### Task
Analyse data of clients terminating their contract with the bank and to choose strategy of retainung them or attracting new clients.  

### Description
More clients leave the bank every month. A model is build using unbalanced data to predict the probability of a client leaving the bank in near future. High F1 sroce was reached with subsequent verification on a test sample. Additionally AUC-ROC score was measured, correlated with F1 score.  

**Trend**  
[![Data Analyst](https://img.shields.io/static/v1?label=Trend&message=Data%20Analyst&color=FF7F50)](#)
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)  

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SKLearn](https://img.shields.io/static/v1?label=tool&message=sklearn&color=cd6133)](#)  
[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=FFBF00)](#)
[![Threshold tuning](https://img.shields.io/static/v1?label=skill&message=Threshold%20Tuning&color=B33771)](#)  

***

[![PROJ_05](https://img.shields.io/badge/go%20to%20PROJECT-05-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/05_mobile_tariff_recommendation)
## [ML Model for Mobile Tariff Recommendation](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/05_mobile_tariff_recommendation)

### Task
Based on the previous data study, build the Machine Learning model for the classification problem, which finds a suitable tariff  

### Description
A system recommending users a more suitable tariff based on their data usage, amount of calls and sms. A classification model with the highest accuracy value is built to select the tariff to be suggested to the user. Correct ratio answers raised to 0.75. Accuracy tested on the test sample.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SKLearn](https://img.shields.io/static/v1?label=tool&message=sklearn&color=cd6133)](#)  
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=FFBF00)](#)
[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Data Visualization](https://img.shields.io/static/v1?label=skill&message=Data%20Visualization&color=9FE2BF)](#)  

***

[![PROJ_04](https://img.shields.io/badge/go%20to%20PROJECT-04-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/04_videogames_market_research)
## [Video Games Markets Research](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/04_videogames_market_research)

### Task
Using historical user and expert ratings date, genres and number of copied sold for various platforms, identify patterns that contribute success of a game  

### Description
An online computer games store has customers worldwide. Historical data about games from open sources is available to identify a potentially popular product. This helps to plan advertising campaigns. Games that are the best bet for being popular and bring most sales are selected. Customer preferences for various regions of the world are noted. A/B-test results revealed that average user ratings between platforms Xbox One and PC do not have statistically significant difference. Another A/B-test showed that average user ratings between genres Action and Sports are different. T-test for independent samples.  

**Trend**  
[![Data Analyst](https://img.shields.io/static/v1?label=Trend&message=Data%20Analyst&color=FF7F50)](#)

**Tools & Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scipy](https://img.shields.io/static/v1?label=tool&message=scipy&color=FFBF00)](#)
[![Seaborn](https://img.shields.io/static/v1?label=tool&message=seaborn&color=CCCCFF)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=matplotlib&color=DE3163)](#)  
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=FFBF00)](#)
[![Data Visualization](https://img.shields.io/static/v1?label=skill&message=Data%20Visualization&color=9FE2BF)](#)
[![Statistics](https://img.shields.io/static/v1?label=tool&message=Statistics&color=cd6133)](#)  


***
