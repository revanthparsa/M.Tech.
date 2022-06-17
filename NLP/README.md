
# Task_1
## DataSet: 
Link : http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Amazon_Instant_Video_5.json.gz

Review rule, for dataset: 
- [overall > 3.0] - positive
- [overall <= 3.0] - negative


## POS_Tag.ipynb
- Generate term statistics:
-- Vocabulary size with word frequencies
-- N-grams
-- POS collections
- Verify Zipf’s law – what is the best fit for your corpus?
- Which set of terms best describe your corpus? 


## Sentiment_Analysis.ipynb
Sentiment Analysis using statistical NLP

- Use the following vector space models 
-- CountVectorizer.
-- TF-IDF.
-- Any external vectorizer (cite the original paper).
- Do sentiment analysis using all (a,b,c) using classical ML techniques 
-- Naive Bayes Model.
-- Decision Tree.
-- Logistic Regression.
- Report metrics [accuracy, f1 score, confusion matrix] for all the combinations in (1 and 2)
- Analyse the results. [Report clearly which vector space model is giving better results on each model used]

## Topic_Extraction.ipynb

Topic analysis and topic (attribute) wise sentiment analysis

- Extract the topics from the reviews using any topic extraction technique of your choice. 
- Report sentences under each topic.
- Analyse whether the topics extracted make sense. Justify your claim with some examples.
- Report topic wise sentiment distribution for the whole repository. Explain the method that you used. Give complete reference of any paper that you use for the purpose. 


# Task_2

## NER_Detection.ipynb
### DataSet : 20Newsgroups dataset
- Run Stanford NER and Spacy NER and extract Named Entities from the data.
- Find the top 100 LOC and PERSON entities from the data set. What is the degree of correlation between the two systems? Consider partial and full matches.

## Custom_NER_Detection.ipynb
### DataSet : 20Newsgroups dataset
- Generate Word2vec, Glove, Fasttext and BERT word vectors for the above corpus.
- Use the NERs detected in previous file to create annotated documents for NER detection. Divide the document collection into training, validation and test data sets. 
Implement a custom NER system (for all 4 vector embedding techniques mentioned in (c)) using LSTM. Compare the results of all models obtained (namely, (i) LSTM with word2vec, (ii) LSTM with glove, (iii) LSTM with fast text,

## Sentiment_Analysis_Using_LSTM.ipynb
### DataSet : AMAZON review Data Set

Develop an 
- Bi-LSTM based sentiment analysis model using (a) word2vec embeddings (b) glove embeddings.
- BERT based sentiment analysis model. 
- Compare the performance on the test set among these models. (Bi-LSTM (with word2vec, glove), BERT) 
- Also, compare with Traditional ML Models developed in Task_1.



