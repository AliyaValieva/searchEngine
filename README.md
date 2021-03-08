# searchEngine

AUTHORS:
	Aliya Valieva Haoyuan Bai
	
LANGUAGE:
	Python 3.9

DESCRIPTION: 
	The project consists of two parts, Indexer.py and SearchEngine.py. 
	The Indexer.py includes lemmatizing words,  calculating the TF-IDF score and handling HTML parsers.  SearchEngine.py is the main module to run,  it connects to the querying index database and retrieve 20 URLS for each query
 
	Collecting statistics through tools including sql and sqlite.



Libraries:
pip install spacy, parser, bs4, lemmatizer, Flask, sqlite3
python -m spacy download en_core_web_sm

Running on:  http://127.0.0.1:5000/ 
	(sample interface with 20 fetched URLS)
  ![Screen Shot 2021-03-08 at 4 57 08 AM](https://user-images.githubusercontent.com/72169983/110261329-9e8f0e80-7fd1-11eb-8772-ce317ab3a35d.png)
