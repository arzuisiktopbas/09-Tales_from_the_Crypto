# Tales from the Crypto
  by Arzu Isik Topbas


## Background

I applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I also applied fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.


#### 1 - Sentiment Analysis

I used the newsapi to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

* Which coin had the highest mean positive score?

  * A: **Bitcoin** had the highest mean positive score with a mean of 0.102, compared to Ethereum's mean positive score of 0.042.
  
* Which coin had the highest negative score?

  * A: **Bitcoin** had the highest compound score with a max of 0.817, compared to Ethereum's max compound score of 0.636.
  
* Which coin had the highest positive score?

  * A: **Bitcoin** had the highest positive score with a max of 0.233, compared to Ethereum's max positive score of 0.155.

#### 2 - Natural Language Processing

In this section, I used NLTK and Python to tokenize the text for each coin. I also looked at the ngrams and word frequency for each coin.
Finally, I generated word clouds for each coin to summarize the news for each coin.

 **Bitcoin Word Cloud**
 
![btc-word-cloud.png](https://github.com/arzuisiktopbas/09-Tales_from_the_Crypto/blob/main/Images/bitcoin_word_cloud.png)

**Ethereum Word Cloud**

![eth-word-cloud.png](https://github.com/arzuisiktopbas/09-Tales_from_the_Crypto/blob/main/Images/ethereum_word_cloud.png)

#### 3 - Named Entity Recognition

In this section, I built a named entity recognition model for both coins and visualize the tags using SpaCy.

![btc-ner.png](https://github.com/arzuisiktopbas/09-Tales_from_the_Crypto/blob/main/Images/Bitcoin_ner.png)

![eth-ner.png](https://github.com/arzuisiktopbas/09-Tales_from_the_Crypto/blob/main/Images/Ethereum_ner.png)

---

