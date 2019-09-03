# Preprocessors-
<h1> Preprocessor functions with some Python NLP libraries/h1>
  
 This notebook shows how to preprocess a text corpus using NLKT, spaCy, Stanford CoreNLP, and Spark NLP.

Preprocessing here means: <b2>

1. Breaking each text up into a list of word tokens. <br>
2. Reducing all word tokens in the corpus to lower case. <br
3. Removing stop words. <br>
4. Reducing each word to dictionary form by lemmatizing. <br>
5. Removing all nonalphabetic tokens such as numbers and punctuation. <br>

Once a corpus is loaded and passed through a preprocessor function, a list (cleanDocs) containing lists of preprocessed tokens for each text in the corpus is returned. 

<br><br>
Not all NLP tasks require the same preproccesing steps, so make sure to only use preprocessing steps needed for your NLP task! For more reading about stop words, refer to: https://medium.com/@wilamelima/why-is-removing-stop-words-not-always-a-good-idea-c8d35bd77214
