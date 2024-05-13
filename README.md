## Sentiment-Analysis using NLP
---
### Overview:
----
This project aims to perform Sentiment Analysis using Natural Language Processing (NLP) techniques, focusing on classifying text data into positive and negative sentiment categories. 
Sentiment Analysis involves analyzing text data to determine the sentiment or opinion expressed within it.
 

### DataSet:
-----
* Source: https://www.kaggle.com/sid321axn/amazon-alexa-reviews/data
* Observations: 3150
* Features: 5

### Data Visualization:
-----
![Screenshot_20240513_124033](https://github.com/alnxha7/Sentiment_Analysis_using_NLP/assets/129566733/00e35bdf-7dc7-4461-8d77-70890804bfe2)

* Its seems that positive class is more than the negative class, which indicate imbalance of class.

![Screenshot_20240513_124022](https://github.com/alnxha7/Sentiment_Analysis_using_NLP/assets/129566733/803a3b82-5e8d-4138-8ec0-95a7b48871bc)

* Moreover there are more people has provided rating of 5 star to Alexa product which indicate that customer is satosfied with the product.

* Wordcloud: All words, Positive and Negative

![Screenshot_20240513_124058](https://github.com/alnxha7/Sentiment_Analysis_using_NLP/assets/129566733/fdf1fc88-2492-444c-87f5-ad9523473cd2)

![Screenshot_20240513_124105](https://github.com/alnxha7/Sentiment_Analysis_using_NLP/assets/129566733/af4f17ca-05be-4428-a69d-9624041e78e1)

![Screenshot_20240513_124111](https://github.com/alnxha7/Sentiment_Analysis_using_NLP/assets/129566733/22eecbae-321e-401f-b811-f83e840602b5)

### Model Building:
----
##### Machine Learning Model:

Random forest algorithm : Training Accuracy : 0.9945553539019963
                          Testing Accuracy : 0.9439153439153439

Xg Boost  : Training Accuracy : 0.971415607985481
            Testing Accuracy : 0.9417989417989417

Decision tree  :  Training Accuracy : 0.9945553539019963
                  Testing Accuracy : 0.9248677248677248

# to run the project

1. Clone the repository:

```bash
git clone https://github.com/alnxha7/Sentiment_Analysis_using_NLP.git
cd Sentiment_Analysis_using_NLP
pip install -r requirements.txt
python app.py
```


### Model Deployment:
----
- Model Deplayment was done using flask.


* Positive Sentiment.
![Screenshot_20240513_125415](https://github.com/alnxha7/Sentiment_Analysis_using_NLP/assets/129566733/c325d3f9-a8c2-448a-a02a-124dcb17d77d)


* Negative Sentiment
![Screenshot_20240513_125507](https://github.com/alnxha7/Sentiment_Analysis_using_NLP/assets/129566733/5e778366-4978-45fa-b374-cfaff4ca1208)


----
<p>Thank You!	
