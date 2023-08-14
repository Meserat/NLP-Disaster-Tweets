<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
       <ul>
        <li><a href="#built-with">Data</a></li>
      </ul>
    </li>
   

  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

# Project Description

[Twitter](https://twitter.com/?lang=en) has become an important communication channel in times of emergency.   
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time.    
Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

# Objective     

[Sentiment analysis](https://en.wikipedia.org/wiki/Sentiment_analysis) is a common use case of [NLP](https://machinelearningmastery.com/natural-language-processing/) where the idea is to classify the tweet as positive, negative or neutral depending upon the text in the tweet.     
This problem goes a way ahead and expects us to also determine the words in the tweet which decide the polarity of the tweet.

In this project [Machine Learning](https://www.geeksforgeeks.org/machine-learning/) models are implemented for predicting that a tweet regarding a disaster is real or fake    
Whole code below is in [Python](https://www.python.org/) using various libraries. Open source library [Scikit-Learn](https://scikit-learn.org/) is used for creating the models.


### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [![Python][Next.js]][Next-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

Template code is provided in the NLP-disaster-Twitter.ipynb notebook file. You will also be required to install neccessary Python packages and the train.csv,test.csv and subsmission.csv dataset file to complete your work. 


### Data

## Dataset Description
# What files do I need?
You'll need train.csv, test.csv and sample_submission.csv.

# What should I expect the data format to be?
Each sample in the train and test set has the following information:

# The text of a tweet
<p>A keyword from that tweet (although this may be blank!)</p>
<p>The location the tweet was sent from (may also be blank)</p>
<p>What am I predicting?</p>
<p>You are predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0.</p


# Files
<p>train.csv - the training set</p



<p>test.csv - the test set</p>
<p>sample_submission.csv - a sample submission file in the correct format</p>



# Columns
<p>id - a unique identifier for each tweet</p>
<p>text - the text of the tweet</p>
<p>location - the location the tweet was sent from (may be blank)</p>
<p>keyword - a particular keyword from the tweet (may be blank)</p>
<p>target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)</p>





















