# amazon_reviews_classification

This is a pet-project, where I use some nlp-methods on data from Amazon Reviews 

[here ypu can download the dataset https://www.kaggle.com/arhamrumi/amazon-product-reviews]

First, I apply a simple Logistic Regression for binary classification;

After that, I train a PipeLine Logistic Regression;

At the end, there is a Random Forest model given.

I will use precision score as a metrics to measure model-quality. My final score is 0.92.


Exploratory analysis: I will process data, look for descriptive statistics, histograms and some examples.
Text transformation: I use nltk to get tokens and get rid of noise.

Some graphs from this work:


The Histogram of the Original Scores:

<img width="327" alt="Снимок экрана 2021-11-11 в 22 14 30" src="https://user-images.githubusercontent.com/82895980/141355582-00aee437-8898-4b65-b8f3-98c80478a56f.png">

Bar-chart of the most popular items and its Scores:
![pic_2](https://user-images.githubusercontent.com/82895980/141355352-a26ed8cc-6700-49d9-a224-596889b33849.png)

Bar-chart of the most active users and their Scores:
![pic_3](https://user-images.githubusercontent.com/82895980/141355374-9c0162c4-9c63-4e7d-8156-b71400640d4b.png)

PR-curve for Pipe-line model:

<img width="345" alt="Снимок экрана 2021-11-11 в 22 12 23" src="https://user-images.githubusercontent.com/82895980/141355404-bb3c2092-9f5e-4f46-8ce6-5b2c562aa6ad.png">
