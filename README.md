## Detecting Mental Disorders on Twitter

## Overview

My final project for a class at Northwestern (Optimization for Machine Learning and Deep Learning) involved pursing a machine learning curiosity.  I decided to research further on text sentiment analysis, particularly learning about the problem in the prediction of mental disorders in social media. 

## Motivation
While research has shown that throughout the decades, rates of diagnosing mental illness have improved, many cases remain undetected.  In the recent age of technology, social media is a popular outlet for people to express their emotions. Moreover, symptoms of mental disorders have shown to be observable through the text in these outlets. Prior studies have indicated that individuals with mental illnesses show deviations in normal language.   Further, I have recently been interested in researching how to analyze, build, and optimize  machine learning/deep learning models that would predict mental disorders in social media (particularly Twitter)and propose technological solutions to try to ameliorate the issue.

## Methodology: 
I determined the best learning tool into the introduction of NLP and sentiment analysis was to utilize a project that detects politcal sentiment shown [here](https://github.com/RonKG/Machine-Learning-Projects-2/tree/master/3.%20NLP_twitter_sentiment_analysis) and modified it to focus on my problem. The results are shown [here](https://github.com/vnoelifant/twitter_detect_depression/blob/master/Twitter_Mental_Disorder_Detection.ipynb).

.In summary the following steps were implemented:

  * Utilized Python’s natural language processing module (NLTK) to clean tweets with a focus on textual indicators of depression
  * Extracted features from tweets using Bag of Words, TF-IDF and word2vec methods
  * Ran features and Naive Bayes machine learning classifier through SciKit Learn Pipeline module. 

## Conclusions
We can see in the results that we have while not a very high accuracy score, the score is not bad, and it's convincing to say we have a good, working algorithm for detecting whether tweets are prone to having a mental disorder. The prediction results are a bit mixed, but at least we do see expected results. However improvements should be explored in the future to enhance the predictions. With the researched machine learning tools, and available models, I believe this project is a great example to build upon further.

## Next steps:
Use more models, such as LSTM CNN to see if the prediction is more accurate, find improved datasets, such as finding those with true labels of mental disorders, figure out alternate ways in pulling test data that may improve the detection (I likely need much more data), predict the actual mental disorder, enhance text/feature exraction, use more labels, such as neutral sentiment labels, explore emojis, research how supportive chat bots can be integrated during real time detection, perhaps with Twitter's Streaming API.

## License/Notes
 * This project is licensed under the MIT License [LICENSE](https://github.com/vnoelifant/twitter_detect_depression/blob/master/LICENSE). This project includes code modifications shown [here](https://github.com/RonKG/Machine-Learning-Projects-2/blob/master/3.%20NLP_twitter_sentiment_analysis/FINAL____twitter_sentiment_twitter.ipynb). License copyright notice and proper citations are included in the [source code](http://localhost:8888/notebooks/twitter_detect_depression/Twitter_Mental_Disorder_Detection.ipynb). 
