# NLP-on-Financial-Statements
#### This is a project from Udacity AI for trading
#### Summary
In this project, we use NLP to extract the sentiments from the 10K document of a list of companies in S&P 500. The documents are first preprocessed, then we analyzed the apperance frequency of words that are listed in the Loughran and McDonald sentiment word lists. The sentiments are used as alpha factors. We then use the Alphalens to analyze the turnover of the factors using historical stock prices.

#### Preprocess
<ul type = "1">
<li>Parse documents with BeautifulSoup</li>
<li>Clean up text</li>
<li>Lemmatize words</li>
<li>Remove Stop works</li>
</ul>

#### Extract sentiment
<ul type = "1">
<li>Generate sentiment TFIDF</li>
<li>Calculate cosine similarities between each tick in time</li>
</ul>

#### Turnover analysis
Use the time-dependent cosine simularity for each stock as the alpha factor. 

#### Resource
<ul type = "1">
<li>Loughran and McDonald sentiment word lists</li>
<li>S&P 500 stock data</li>
</ul>

