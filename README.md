# Sentiment-analysis-using-NLTK-Python
Sentiment analysis text classification using NLTK library of Python, Provide sentiment score and category as positive and negative

## Requirements 
```
pip install nltk
pip install scikit-learn
```

## Download all the packages of NLTK by using following command in python IDLE or command prompt
```
import nltk
nltk.download()
```
### It will popup one window which display packages of nltk click on All then download all packages from that.

## Now execute following python files

### Frist execute makeModel.py file. It will use sklearn classifier algorithms to classify text sentiment and generate pickle file to store trained model
```
python makeModel.py
```

### Second execute test.py file. It contains some testing sentance which call sentiment_mod file to generate sentiment, You can input your sentance also.

``` 
python test.py
```
