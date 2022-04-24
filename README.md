<center><h1>NLP (Natural Language Processing)</h1></center>
<p> <b> Data set : </b>https://www.kaggle.com/datasets/kazanova/sentiment140?select=training.1600000.processed.noemoticon.csv </p>

<h2>Understanding Data Set</h2>
<br>
    Data Set ada 6 kolum
    <li>target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
    <li>date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
    <li>flag: The query (lyx). If there is no query, then this value is NO_QUERY.
    <li>user: the user that tweeted (robotickilldozr)
    <li>text: the text of the tweet (Lyx is cool)
        
   <h3>Rename data set jadi : twitter16m.csv </h3>
       
 Library :
 <li> SpaCy
   
   <center><h2>Yang akan dipelajari</h2></center>
     
 <h2> General Feature Extraction </h2>
               <li>File loading
               <li>Word counts
               <li>Characters count
               <li>Average cahr per word
               <li>Stop words count
               <li>Caount #hashtags and @mentions
               <li>If numeric digits are present in tweets
               <li>Upper case word counts
   <br>                
<h2> Processing and Cleaning </h2>
<li>Lower Case
<li>Contraction to Expansion
<li>Email removal and counts
<li>Removal of RT
<li>Removal special characaters
<li>Removal of multiple spaces
<li>Removal Html TAGS
<li>Removal of accented chars
<li>Removal of stop Word
<li>Conversion into base from of words
<li>Common Occuring words Removal
<li>Rare Ocuring Words Removal
<li>Word Cloud
<li>Spelling Correction
<li>Tokenization
<li>Lemmatization
<li>Detecting Entities Using NER
<li>Noun Detection
<li>Language Detection
<li>Sentence Translation
<li>Using Inbuilt Sentiment Clasifier
   <br>                
<h2>Advanced Text Processing and Feature Extraction</h2>
<li>N-Gram, Bi-Gram etc
<li>Bag of Words (BoW)
<li>Term Frequency Calculation TF
<li>Inverse Document Frequency
<li>TFIDF Term Frequency Inverse Document
<li>Word Embedding Word2Vec using SpaCy
    <br>
    <h2>Machine Learning Models for Text Clasification</h2>
<li>SGDClassifier
<li>LogisticRegression
<li>LogisticRegressionCV
<li>LinerarSVC
<li>RandomForestClasifier
