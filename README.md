# covid-rumor-analysis

An NLP project aiming at detecting and analyzing covid-19 rumors on Twitter.

Total score: 28/30

# Research questions: 

Provide accurate rumor detection solutions, identify rumors from a set of covid tweets and study the characteristics of covid rumors. 

In particular,

(i) what unique features differentiate rumor users? 

(ii) lexically, what are salient hashtags/tokens of rumor tweets 

(iii) topically, what are major rumor categories? How do they evolve? 

(iv) finally, does the sentiment and emotion distribution on rumors and retweets vary from truth? We present our task-based answers as follows.

# Summary:

## Task I - coivd rumor detection

Models used: Naive Bayes, Logistic Regression, BERT, BERTweet, and an ensemble.
Results on Kaggel: highest F1 score was 0.934

## Task II - explanatory analysis of covid rumor tweets

"Applying our model on the covid dataset (around 200k), we recognized 2060 rumors and 13896 replies in total, with their counterparts being 22802 and 107150 correspondingly. The tweets were produced by 6644 unique users, between January 9th and August 1st."

We also analyzed the charateristics of rumor users from the meta data (e.g., #followers, #friends, #tweets), hashtags and bigrams rumor and non-rumor tweets (see the wordcloud), performed an LDA analysis to extract the rumor topics and the salient words of each latent topic, topic evolvation over time (see the stacked percentage diagram), and sentiment and emotion analysis using pretrained models.


The PDF report is only part of the final report (including the introduction, report structure and some tables and figures) for you to have an overview of our work. 
