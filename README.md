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

### Project Goal
Optimize electricity consumption at the steel plant. Develop ML model for predicting steel temperature.  

### Project Description
Given data from various indicators of a steel plant.
The task is to develop ML model to predict final temperature of steel with MAE at least 6.8.  

Exploring the available data, it types, missings, duplicates, basic statistics, plot graphs.  
Data was cleaned and preprocessed. Some missings in data was filled some data had to be deleted. 
Then data was aggregated from 7 different tables to the one. 10 new features was generated.
Three different ML models were trained and tuned on cross-validation with feature transformation via pipeline. After determining the best model, we've evaluated the importance of the features. Three ifferent methods was used to explore feature importances. Based on the study of feature importances a new lightweight model was developed with only 10 features (instead of 33) and MAE below 5.4.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SK-Learn](https://img.shields.io/static/v1?label=tool&message=sk-learn&color=cd6133)](#)  

[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=B33771)](#)

***

[![PROJ_13](https://img.shields.io/badge/go%20to%20PROJECT-13-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/13_cv_age_recognition)
## [Age Recognition Using CV Deep Learning Model](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/13_cv_age_recognition)

### Project Goal
Develop a CV model to recognise an age of customers by their photo.

### Project Description
Supermarket chain Bread&Salt introduces a computer vision system for processing customer's photos. Photo fixation at checkout area will help to determine the age of customers in order to:  
- Analyze purchases and offer products that may be of interest to buyers of this age group;
- Control the conscientiousness of cashiers when selling alcohol;
- Security reasons.

Study summary:
THe exploratory analysis was conducted first. There are not many photos were available. Therefore the augumentation was implemented.
The pretrained Resnet-102 neural network model was finetuned for the purpose of stidy. The last two layers of model were replaced, respectively, with a connected layer with one output neuron and leaky ReLU activation. The final value of the MAE metric on the validation sample was 5.91.

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Keras](https://img.shields.io/static/v1?label=tool&message=Keras&color=40407a)](#)
[![Tensorflow](https://img.shields.io/static/v1?label=tool&message=Tensorflow&color=cd6133)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)


[![DL](https://img.shields.io/static/v1?label=skill&message=DL&color=1B9CFC)](#)
[![CV](https://img.shields.io/static/v1?label=skill&message=CV&color=B33771)](#)
[![RE](https://img.shields.io/static/v1?label=skill&message=RE&color=B33771)](#)

***

[![PROJ_12](https://img.shields.io/badge/go%20to%20PROJECT-12-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/12_nlp_toxic_comments_detection)
## [Natural Language Processing: Toxic Comments Detection Using ML](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/12_nlp_toxic_comments_detection)

### Project Goal
Develop NLP model to detect toxic comments.

### Project Description
Online store "Wikishop" launches a new service. Now users can edit and supplement product descriptions, just like in wiki communities. The store needs a tool to speedup the moderation of product desctiption commentaries by automating their tone assessment. The tool will use an ML model which can detect toxic comments and submit them for moderation.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SK-Learn](https://img.shields.io/static/v1?label=tool&message=sk-learn&color=cd6133)](#)  
[![Spacy](https://img.shields.io/static/v1?label=tool&message=Spacy&color=cd6133)](#)  
[![NLTK](https://img.shields.io/static/v1?label=tool&message=nltk&color=cd6133)](#)  
[![TF-IDF](https://img.shields.io/static/v1?label=tool&message=tf-idf&color=cd6133)](#)  

[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![NLP](https://img.shields.io/static/v1?label=skill&message=Natural%20Language%20Processing&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=B33771)](#)

***

[![PROJ_11](https://img.shields.io/badge/go%20to%20PROJECT-11-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/blob/main/11_timeseries_prediction/11_timeseries_prediction.ipynb)
## [Number of Taxi Orders Prediction](https://github.com/ivan-aleshin/yandex-practicum-projects/blob/main/11_timeseries_prediction/11_timeseries_prediction.ipynb)

### Project Goal
.  

### Project Description
.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SK-Learn](https://img.shields.io/static/v1?label=tool&message=sk-learn&color=cd6133)](#)  

[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=B33771)](#)

***

[![PROJ_10](https://img.shields.io/badge/go%20to%20PROJECT-10-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/10_car_price_prediction)
## [Car Price Prediction](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/10_car_price_prediction)

### Project Goal
.  

### Project Description
.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SK-Learn](https://img.shields.io/static/v1?label=tool&message=sk-learn&color=cd6133)](#)  

[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=B33771)](#)

***

[![PROJ_09](https://img.shields.io/badge/go%20to%20PROJECT-09-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/09_personal_data_protection_method)
## [Development of Personal Data Protection Algorithm](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/09_personal_data_protection_method)

### Project Goal
.  

### Project Description
.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SK-Learn](https://img.shields.io/static/v1?label=tool&message=sk-learn&color=cd6133)](#)  

[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=B33771)](#)

***

[![PROJ_08](https://img.shields.io/badge/go%20to%20PROJECT-08-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/08_ml_in_metall_industry)
## [Prediction of Enrichment Efficiency in the Recovery of Gold from Ore](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/08_ml_in_metall_industry)

### Project Goal
.  

### Project Description
.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SK-Learn](https://img.shields.io/static/v1?label=tool&message=sk-learn&color=cd6133)](#)  

[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=B33771)](#)

***

[![PROJ_07](https://img.shields.io/badge/go%20to%20PROJECT-07-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/07_ml_oil_fields_prediction)
## [Exploration of New Oil Fields Regions Using ML Models](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/07_ml_oil_fields_prediction)

### Project Goal
.  

### Project Description
.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SK-Learn](https://img.shields.io/static/v1?label=tool&message=sk-learn&color=cd6133)](#)  

[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=B33771)](#)

***

[![PROJ_06](https://img.shields.io/badge/go%20to%20PROJECT-06-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/06_bank_churn_prediction)
## [Bank Customer Churn Prediction](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/06_bank_churn_prediction)

### Project Goal
.  

### Project Description
.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SK-Learn](https://img.shields.io/static/v1?label=tool&message=sk-learn&color=cd6133)](#)  

[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=B33771)](#)

***

[![PROJ_05](https://img.shields.io/badge/go%20to%20PROJECT-05-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/05_mobile_tariff_recommendation)
## [ML Model for Mobile Tariff Recommendation](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/05_mobile_tariff_recommendation)

### Project Goal
.  

### Project Description
.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SK-Learn](https://img.shields.io/static/v1?label=tool&message=sk-learn&color=cd6133)](#)  

[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=B33771)](#)

***

[![PROJ_04](https://img.shields.io/badge/go%20to%20PROJECT-04-87CEEB)](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/04_videogames_market_research)
## [Video Games Markets Research](https://github.com/ivan-aleshin/yandex-practicum-projects/tree/main/04_videogames_market_research)

### Project Goal
.  

### Project Description
.  

**Trend**  
[![Data Scientist](https://img.shields.io/static/v1?label=Trend&message=Data%20Scientist&color=218c74)](#)

**Tools and Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SK-Learn](https://img.shields.io/static/v1?label=tool&message=sk-learn&color=cd6133)](#)  

[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![Feature Genaration](https://img.shields.io/static/v1?label=skill&message=Feature%20Generation&color=B33771)](#)
[![EDA](https://img.shields.io/static/v1?label=skill&message=EDA&color=B33771)](#)

***
