NLP lab programs ,solutions for following problems:
1. Perform word tokenization and sentence tokenization for the long paragraph using NLP libraries
like:
a. Tokenization Using Python's Inbuilt Method
b. Tokenization Using Regular Expressions(RegEx)
c. Tokenization Using NLTK
d. Tokenize as a list Using SpaCy
e. Tokenization using Keras
f. Check token is Alphabet/Punctuation/Number/Currency or Not using Spacy and display
appropriate messages for every token.

2. Consider students.txt and perform the following operations:
a. Tokenize the email ids from the given students.txt using Spacy
b. Tokenize all email ids from the given students.txt using NLTK
c. Collecting dataset websites from a book paragraph using Spacy
Text='''
Look for data to help you address the question. Governments are good sources because data
from public research is often freely available. Good places to start include
http://www.data.gov/, and http://www.science.gov/, and in the United Kingdom,
http://data.gov.uk/. Two of my favorite data sets are the General Social Survey at
http://www3.norc.org/gss+website/, and the European Social Survey at
http://www.europeansocialsurvey.org/. The current representation will be formed by a well-
organized collection of agents, previously structured in a dynamic, control-based manner. This
collection of agents will be built based on the analysis of activations of conception and
structuring agents that intercommunicate. Having first deployed an intent, a global
interpretation of the system’s situation is formed by means of questionings, qualifying aspects
of things, memorized cases, development of numerous cognitive aspects by activating agents
that operate proper scaling up, all of which will allow for the efficient emergence of the
representation. The system’s interpretation of this collection of agents will take the form of
http://www.systemsurvey.org/ a network of dynamic knowledge of apprehensions, operating
through questions in a steadily activated loop. This knowledge network will be activated by
the system and further developed based on inter-agent relations that will result in significant
aggregations of knowledge, structures of dynamic knowledge with appropriate (domain.com)
characteristics.
'''
d. Extract all money transaction from below sentence along with currency using Spacy.
Transactions = "Aron gave two $ to Shawn, Smith gave 500 $ to Johan"
Output should be,
two $
500 $

3. Implement text preprocessing techniques on email dataset using NLTK libraries and perform
following operations:
a. Rename columns
b. Expand contractions
c. Lower case
d. Remove punctuations
e. Remove digits and word containing digits
f. Remove stop words and specified words

4. Perform following stop word operations on email dataset using Spacy, Gensim and NLTK
libraries
a. Display existing stop words in the default list
b. Removing stop words from the default list
c. Adding stop words to the default list
d. Apply stop word elimination to the email Dataset

5. Generate n-gram representation for the given corpus and perform following operations on the
corpus:
a. Preprocess the corpus for n-gram representation
b. Display all tokens, distinct tokens and frequency of tokens in the corpus
c. Bi-gram and frequency representation using user defined functions
d. Tri-gram and frequency representation using user defined functions

6. Implement following operations on the tweets dataset using NLTK libraries:
a. Data cleaning
b. Rank most frequently occurring 15 n-grams (bigram and trigrams) in the given tweets
dataset
c. Visualize most frequently occurring 15 n-grams (bigram and trigrams) in the given
tweets dataset

7. Perform following operations on the given text data:
a. Stemming using porter stemmer, snowball stemmer, lancaster stemmer
b. Lemmatization using spacy lemmatizer, wordnet lemmatizer, textblob lemmatizer
c. Get all possible lexemes for each word in the sentence = "the bats saw the cats with best
stripes hanging upside down by their feet" using any lemmatizer.

8. Perform minimum edit distance for the given two strings using:
a. User defined function
b. Built in function
