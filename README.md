# Detecting-Fake-News
Experiments on different embedding techniques performance at detecting Fake News

The data is split into three .csv files:
  - True.csv - contains all true articles
  - Fake.csv - contains all 'fake news' articles
  - FakeNews.csv - contains only 'fake news' articles
  
 Download the .ipynb file and run the cells from top to bottom.
 There are four different models that are compared:
  - Count model: uses Bag of Words encoding
  - Tf-Idf model: uses Term Frequency - Inverse Document Frequency
  - Word2Vec model: uses Word2Vec embeddings as the input to the model
  - Doc2Vec model: uses Doc2Vec embeddings as the input to the model
