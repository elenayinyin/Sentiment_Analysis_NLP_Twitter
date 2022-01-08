# Sentiment_Analysis_NLP_Twitter
**Objective:**
- Compute the sentiment of text information based on tweets posted recently on Canadian Elections.
- Get insights into the Canadian Elections.
- Answer the research question: “What can public opinion on Twitter tell us about the Canadian political landscape in 2021?”
- Apply machine learning algorithms to the task of text classification.

**Attachments:**
- **sentiment_analysis.csv:** generic tweets used to train models.
- **Canadian_elections_2021.csv:** actual testing data.
- **sentiment_analysis_twitter:** IPython Notebook detailing the analysis performed.

**Process:**
- Clean the text data.
- Do exploratory data analysis to determine the political party of a given tweet, examine distribution of the political affiliations of the tweets, and visualize sentiments associated to different parties;
- Use both types of features (Bag of Words and TF-IDF), train seven models on the training data, including logistic regression, k-NN, Naive Bayes, SVM, decision trees, Random Forest and XGBoost.
- Use tweets with negative sentiments as the dataset, train multi-class classification models to predict the reason for the negative tweets.

**Findings:**
- Conservative & liberal political parties are more controversial. Conservative has the highest number of tweets about 666, and liberal has the second highest number of tweets about 482. Both of these two parties have around 55% positive-sentiment and 45% negative-sentiment tweets.
- Logistic regression with bag-of word feature has the highest scores on testing generic dataset; other models such as the XgBoost and multinomial naive bayes also perform well. Choose to use logistic regression.
- By visualizing sentiment predictions of 4 parties, NLP analytics is useful for election campaigns especially if the political party is controversial online, so that we can have enough tweet data to do training analysis. For liberal and conservative parties, the number of correct predictions of sentiment is two to three times larger than the number of incorrect predictions.
- Find the top 50 non-stop words of positive sentiment and negative sentiment shown below.
