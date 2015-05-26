Step 1: Data Collect
Collect tweets from twitter related to 3 select candidates. Set up Twitter API to work on R environment.   And extract text from loaded tweets related to Indian election.

Step 2: Preprocessing extract text 
Here, task is to convert all unstructured data into structured date by removing duplicate tweets, punctuation, unnecessary whitespace, non- english characters, irrelevant links.

Step 3: Perform Sentiment Analysis
Classify the text based on emotions categories and polarity. Learning method has been used here to classify the text. Separate the text by emotions and visualize the words with a comparison cloud. Eventually sentiment analysis speaks the overall contextual polarity of a document.

Step 4: Estimate Tweets sentiment
Get the score of negative and positive sentiment by performing “Sentiment scoring algorithm”. Here to get the result, “Breen’s Approach” has been considered. This method is called Lexicon which is nothing but word dictionary.

Step 5: Text mining 
First, transforming text by building a corpus, that is a collection of text documents. Pre-processing text includes removing stopwords, changing letters to lower case, removing punctuations and numbers. After that, stemming words t retrieves the root from, so that words look normal. TermDocumentMatrix function provides the frequency of terms in document and also importance of the words by using performing findAssocs function. 
