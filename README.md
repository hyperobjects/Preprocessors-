# Preprocessor Functions with Python NLP libraries

After corpus creation, preprocessing is the first step for many NLP tasks. In these preprocessor examples, all the .txt files from a local directory are opened and put in a list of documents (docs) which constitutes the text corpus. Once a corpus is loaded and passed through a preprocessor function, a list (cleanDocs) containing lists of preprocessed tokens for each text in the corpus is returned. For notebook readability, I've commented out the return. 
<h2> Project Description:</h2>
  
This notebook shows how to preprocess a text corpus using NLKT, spaCy, Stanford CoreNLP, and Spark NLP. The corpus in these examples is a collection of speeches by Dr. Martin Luther King.  

Preprocessing here means: <br>

1. Breaking each text up into a list of word tokens. <br>
2. Converting all characters in strings to lower case. <br>
3. Removing stop words. <br>
4. Reducing each word to dictionary form by lemmatizing. <br>
5. Removing all nonalphabetic tokens such as numbers and punctuation. <br>

<br>
Not all NLP tasks require the same preproccesing steps, so make sure to only use the steps needed for your project! 
For more reading about stop words, refer to: https://medium.com/@wilamelima/why-is-removing-stop-words-not-always-a-good-idea-c8d35bd77214

<h2> Dependencies:</h2>

pip install -U nltk <br>
nltk.download()  # execute in python and select which NLTK corpora to download<br>

pip install -U spacy <br>
python -m spacy download en_core_web_sm <br>

pip install stanfordnlp <br>
stanfordnlp.download('en') # download English language model <br>

pip install spark-nlp==2.2.1 <br> 

<b>Note</b>: Check the official links for documentation on what other language models are supported as you are not limited to working with English language data. 

https://www.nltk.org/install.html <br> 
https://nlp.johnsnowlabs.com/docs/en/install <br> 
https://stanfordnlp.github.io/stanfordnlp/ <br>
https://spacy.io/usage <br>

