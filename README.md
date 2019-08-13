# sentiment_analysis_twitter
Twitter sentiment analysis for any topic with tweepy library

Sentiment analysis is used to analyse text from a social medias like twitter, customer reviews from e-commerece websites like amazon to predict the sentiment of the tweets or product reviews. 
      The sentiment may be positive, negative, or neutral.This has a great role in understanding the 
sentiment of people towards a specific topic or product for which we wish to start a business.

### Rule-Based Sentiment Analysis:

It uses a lexicon of sentiment related words to predict the sentiment of a sentence.

The lexicon has many sentiment related words with each word corresponding to a positive or negative value.When a sentence is given for sentiment analysis, the number of words with positive and negative points are counted. If the number of words with positive point is more than that of negative ones, then the polarity of sentiment is positive :) and vice versa :(

### Dependencies

1. **Tweepy** is the library used for accessing the twitter API which is required for collecting the tweets for sentiment analysis.
2. **Pandas** is used for dataset(tweets) manipulation.
3. **NLTK** is required for predicting the score of sentiment or polarity of sentiment based on vader lexicon.


You can get create a twitter API from [here](https://developer.twitter.com/apps).


## More Resources 

1. [Sentiment Analysis - Concept & Applications](https://towardsdatascience.com/sentiment-analysis-concept-analysis-and-applications-6c94d6f58c17)

2. [Sentiment Analysis In Business Applications](https://towardsdatascience.com/applications-of-sentiment-analysis-in-business-b7e660e3de69)

3. [Types, Tools and Use Cases of Sentiment Analysis](https://www.altexsoft.com/blog/business/sentiment-analysis-types-tools-and-use-cases/)

4. [10 Examples of Sentiment Analysis To Improve Your Products](https://www.wonderflow.co/sentiment-analysis-examples/)

## Research Papers

Here are some research which solves some specific problem using sentiment analysis

   1. [Sentiment Analysis of Hotel Aspect Using Probabilistic Latent Semantic Analysis, Word Embedding and LSTM](https://www.researchgate.net/publication/333972257_Sentiment_Analysis_of_Hotel_Aspect_Using_Probabilistic_Latent_Semantic_Analysis_Word_Embedding_and_LSTM) 

   2. [Embedded Emotion-based Classification of Stack Overflow Questions Towards the Question Quality Prediction](https://www.researchgate.net/publication/305324293_Embedded_Emotion-based_Classification_of_Stack_Overflow_Questions_Towards_the_Question_Quality_Prediction)

   3. [State of the Art Papers - Papers With Code](https://paperswithcode.com/task/sentiment-analysis)

   4. [Generating Music from Literature Using Topic Extraction and Sentiment Analysis](https://ieeexplore.ieee.org/document/8253722/authors#authors)