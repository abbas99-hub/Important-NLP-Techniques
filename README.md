# Important-NLP-Techniques
In this tutorial, I have covered some basic important Natural language Processing techniques needed when dealing with text data.

Important Concepts for NLP is as follows:

1) Text Normalization:
A) Stemming
B) Lemmatization

2) Text Preprocessing:

It includes removing stopwords, removing noise in text data, removing unwanted data, converting text data in lower format and many more.

3) Keyword Extraction:

Keyword Extraction is the process of extracting important keywords from complete data. In simple words,it is a text analysis technique that automatically extracts the most used and most important words and expressions from a text. It helps summarize the content of texts and recognize the main topics discussed.

Keyword extraction uses machine learning artificial intelligence (AI) with natural language processing (NLP) to break down human language so that it can be understood and analyzed by machines. It’s used to find keywords from all manner of text: regular documents and business reports, social media comments, online forums and reviews, news reports, and more.

Imagine we want to analyze thousands of online reviews about our product. Keyword extraction helps us sift through the whole set of data and obtain the words that best describe each review in just seconds. That way, we  can easily and automatically see what our customers are mentioning most often, saving our teams hours upon hours of manual processing.

4) Named Entity Recognition:

Named Entity Recognition (NER) is a standard NLP problem which involves spotting named entities (people, places, organizations etc.) from a chunk of text, and classifying them into a predefined set of categories. Some of the practical applications of NER include:

Scanning news articles for the people, organizations and locations reported.
Providing concise features for search optimization: instead of searching the entire content, one may simply search for the major entities involved.
Quickly retrieving geographical locations talked about in Twitter posts.

5) Chunking:


Chunking is a process of extracting phrases from unstructured text. Instead of just simple tokens which may not represent the actual meaning of the text, its advisable to use phrases such as “South Africa” as a single word instead of ‘South’ and ‘Africa’ separate words.
Chunking works on top of POS tagging, it uses pos-tags as input and provides chunks as output. Similar to POS tags, there are a standard set of Chunk tags like Noun Phrase(NP), Verb Phrase (VP), etc. Chunking is very important when you want to extract information from text such as Locations, Person Names etc. In NLP called Named Entity Extraction.
There are a lot of libraries which gives phrases out-of-box such as Spacy or TextBlob. NLTK just provides a mechanism using regular expressions to generate chunks.
Let’s dive deeper..
We will consider Noun Phrase Chunking and we search for chunks corresponding to an individual noun phrase. In order to create NP chunk, we define the chunk grammar using POS tags. We will define this using a single regular expression rule.
The rule states that whenever the chunk finds an optional determiner (DT) followed by any number of adjectives (JJ) and then a noun (NN) then the Noun Phrase(NP) chunk should be formed.

6) WordCloud:

Word Cloud is a data visualization technique used for representing text data in which the size of each word indicates its frequency or importance. Significant textual data points can be highlighted using a word cloud. Word clouds are widely used for analyzing data from social network websites.
