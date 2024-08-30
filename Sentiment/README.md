# Comprehensive Exploratory Data Analysis of News Headlines:
 # Descriptive Statistics, Text Analysis, Time Series, and Publisher Contributions
 In this assignement we have address the following things
  1. Data preprocessing(we have used the news dataset)
  2. Descriptive Statistics
  -> Obtain basic statistics for textual lengths (like headline length).
  -> Count the number of articles per publisher to identify which publishers are most active.
 -> Analyze the publication dates to see trends over time, such as increased news frequency on particular days or during specific events.
  3. Exploratory Data Analysis
  4. Text Analysis
  In the text analysis we have conducted sentiment analysis and Topic modeling using various methods on the headline features
  # Sentiment Analysis
Sentiment analysis was performed on the headlines to assess the emotional tone of the news. In
this phase, we have used SentimentIntensityAnalyzer to analyze the sentiment of the text. We have
also used polarity_scores (text=x) to calculate the sentiment scores for the provided text, where x
is the headline text. Finally, we used the label_sentiment(score) to label the sentiment as 'Positive', 'Negative', or 'Neutral' based on the score value. The distribution of sentiment across the dataset is as follows:Figure 4: Sentiment distributions
# Topic Modeling
Topic modeling is a text analysis technique used to uncover the underlying themes or topics within
a collection of documents. In our case, we have used the Latent Dirichlet Allocation (LDA)
approach. LDA assumes that each document is a mixture of topics and each topic is a mixture of
words. It finds the underlying topics by analyzing word distributions across the documents. In the
vectorization phase, we used CountVectorizer to convert the text into numerical features.
  # Time Series Analysis
  in this phse We have answered 
  How does the publication frequency vary over time? Are there spikes in article publications related to specific market events?
  Analysis of publishing times might reveal if there’s a specific time when most news is released, which could be crucial for traders and automated trading systems.
  # Publisher analysis
  We have answered the question 
  Which publishers contribute most to the news feed? Is there a difference in the type of news they report?
  If email addresses are used as publisher names, identify unique domains to see if certain organizations contribute more frequently.

