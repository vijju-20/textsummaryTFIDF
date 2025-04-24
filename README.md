#  TEXT SUMMARIZATION TOOL

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: CHINTAM VIJAYA LAKSHMI

*INTERN ID*: CT06WC94

*DOMAIN*: ARTIFICIAL INTELLEGENCE

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOS

##Internship-Task 1
#create a tool that summarizes lengthy articles using natural language processing techniques.
#for all natural language processing requirements eg:text summarization, we can use libraries like nltk,spacy and transformers 
#NLP models, including machine learning algorithms, cannot directly process raw text. Tokenization transforms text into a format that machines can understand and analyze. 
#the sent_tokenize function from the nltk.tokenize module breaks down text into a list of individual sentences
#input to the model(a large text) is given through a text file and this large text will be summarized using TF-IDF vectorizer technique
#open the input file in read mode and copy all the contents into a string variable 
#this sent_tokenize function takes the input text and splits it into individual sentences, returning a list of tokens
#TFIDFVectorizer is a simple and efficient implementation of the TF-IDF transformation algorithm, suitable for use in various machine learning applications
#Tfidfvectorizer aim to convert a collection of raw documents to a matrix of TF-IDF feature
#TFIDF is a way to create a vector representation of a document by averaging all the document's word weights.
#creating an instance of the TfidfVectorizer class and remove the stop words from the input text
#use fit_transform method in the vectorizer object to read the input text and collect the necessary statistics (like term frequency and inverse document frequency) 
#from the input data (which is list of tokens) and transforms the input data into the corresponding TF-IDF representation (numerical format).
#calculate the sentence score for all the sentences in the tf_idf matrix
#print the number of elements in the matrix 
#print the number of tokens 
#calculate the average sentence score 
#if the sentence score is greater than average score then include the sentence else skip it
#print the summarized output
