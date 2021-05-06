#  NLP_Vaccine_SentimentAnalysis_Tweets

![](C:\Users\DELL\FLATIRON_LEARN\Project_MS_Studio\README_imges\Vaccine_tweet.png)

Currently we know COVID-19 continues to be a global crisis, there is one way to get out of the pandemic completely and that is Vaccination. The sentiment towards the vaccine has always been a mixed one as there always is a theory why one should have it and there is another which says not to have.  

Just for a basic understanding A **vaccine** works by training the **immune** system to recognize and combat pathogens, either **viruses or bacteria**. The **sentiment** towards having vaccine has been always a mixed and Vaccine sentiment has too not dramatically changed. The tweeting community has become a strong one but is no different when it comes to the sentiment and the feel is that the tweeting community can play a great role in changing but the question is are they doing enough ?

**The goal here is to do sentiment analysis in the tweet community and conclude on how the community can further improve in shifting the sentiment**

The Process followed & libraries used

- **Pulled in Data using TWINT**
- **For EDA used Pandas - Numpy - Seaborn - Matplotlib** 
- **Used NLTK for word tokenizing - stopwords - lemmatizing - porter stemmer- FreqDist**
- **Nltk-util for ngrams**
- **For adding Sentiment used Text blob**
- **scikit learn for feature extraction, **(count vectorization,Tfid vectorization), **model selection**, **Stratified Shuffle Split**, **linear_model** - LogisticRegression, **metrics** confusion_matrix, **naive_bayes-** MultinomialNB, **ensemble**-RandomForestClassifier, **tree**DecisionTreeClassifier
- **Bag of words using genism & Latent Dirichlet Allocation (the LDA Model)**
- **Python LDA for visualization (pyLDAvis**)
- **Wordcloud for visualisation**



**TWINT**

*Total tweets collected were 25774 from 2013-02-17 to  2021-05-02

*Analysed tweets were 24934 from 2020-01-01 to 2021-05-02 

*6 Search Words = "vaccine" "vaccination“ "immunization" "Pfizer" "Moderna" "Johnson“

**Exploratory Data Analysis**

1. Tweets by NEWS channel handle within collected data from 2013-02-17 to  2021-05-02
   - @nytimes **(49.9m followers) has only 86 tweets regarding Vaccine
   - **@** **cnnbrk****** **(60.2m followers) has only 47 tweets regarding** **Vaccine \*** * **most popular tweeter news account**
   - **@** **usnews**  **(158.1k followers) has no tweets regarding Vaccine**
2. ![](C:\Users\DELL\FLATIRON_LEARN\Project_MS_Studio\README_imges\Tweets_by_month.png)

- Clearly the number of tweets with regards to vaccine has been the highest month of April 2021
- Jan 2021 & Feb 2021 had a dip in the number of tweets after taking off in Dec 2020



3 . **TEXT BLOB**

**The overall tweets that we came across has been positive and objective**

![](C:\Users\DELL\FLATIRON_LEARN\Project_MS_Studio\README_imges\SentimentOverall-1620305672675.png)

**Sentiment Polarity** 

![image-20210507021319702](C:\Users\DELL\FLATIRON_LEARN\Project_MS_Studio\README_imges\image-20210507021319702.png)

![](C:\Users\DELL\FLATIRON_LEARN\Project_MS_Studio\README_imges\SentimentPolarity.png)