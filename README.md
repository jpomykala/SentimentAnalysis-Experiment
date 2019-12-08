# Getting Started

Article: http://www.hausmanmarketingletter.com/sad-state-sentiment-analysis/

"Recent experiments suggest sentiment analysis data is LESS accurate than a coin toss (accuracy 50%). That’s really scary if your brand makes strategic decisions based on sentiment analysis."

Used dataset: https://ai.stanford.edu/~amaas/data/sentiment/


## Tech stack:
- Java 11
- Spring Framework (just for dependency injection)
- Stanford Core NLP


## Results:

Algorithm was right in ~50% cases.

![results](https://github.com/jpomykala/SentimentAnalysis-Experiment/blob/master/images/results.png?raw=true)



![memory](https://github.com/jpomykala/SentimentAnalysis-Experiment/blob/master/images/visual-vm.png?raw=true)


## How to load different data?
Check `DataReader.java` class. You can setup your own directories to positivie and negative reviews.


