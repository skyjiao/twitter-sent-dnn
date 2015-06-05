# twitter-sent-dnn
Twitter Sentiment Analysis using Convolutional Neural Network(CNN)

A web app that allows to:

- predict sentiment "positiveness" for tweets
- gain an overview of the "positiveness" of [hashtags](https://support.twitter.com/articles/49309-using-hashtags-on-twitter#)

## How to use it?

```
>> from sentiment import sentiment_score
>> print sentiment_score(u"I love you")
0.9999
```


## Demo

Click [here](https://twitter-sentiment-cnn.herokuapp.com/)

## Algorithm


Please refer to [A Convolutional Neural Network for Modelling Sentences](http://nal.co/papers/Kalchbrenner_DCNN_ACL14) for more information about the algorithm.

## Technical choices

- [Tornado](http://www.tornadoweb.org/en/stable/) as the web framework
- [Theano](http://deeplearning.net/software/theano/) as the neural network training implementation
- [Scipy](http://www.scipy.org/) as the neural network classification(online version) implementation

## Training techniques

1. Fan-in, fan-out initialization
2. Dropout
3. AdaDelta

## Contributors
Han Xiao and Yao Lu
