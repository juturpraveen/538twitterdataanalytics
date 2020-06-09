# 538twitterdataanalytics
## Data analytics of Russian troll tweets from fivethirtyeight.com
Source: http://tweettracker.fulton.asu.edu/tda/TwitterDataAnalytics.pdf

### Data Preprocessing pipeline steps
1. Lowercase
2. Tokenize
3. Remove stopwords
4. Stemming
5. Vectorization

### Topic Modelling
- Question: What users/people are talking about?
- Latent Dirichlet Allocation(LDA) algorightm is used.
- Each topic contains all words of corpus. Each word is given proabability score of it belonging to that topic.

### Sentiment Analysis
- Question: How users/people are saying it?
- Associate text with a sentiment score, a positive or negative emotional score.
- Lexicon, a dictionary of words with positive and negative scores is needed.
- Source of this lexicon is important.
- Naive bayes classifier can be used.

