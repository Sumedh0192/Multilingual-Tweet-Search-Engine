################# Multi Lingual Search Engine ################

### Concept: 
Creating a platform for searching multi-lingual tweets related to specified topics. This is an implementation under Information Retrieval.

### Implementation:
* Setup SOLR on an EC2 instance of AWS cloud.
* Collected more than 100000 Tweets using twitter rest api for diverse topics in multiple languages.
* Passed the tweets to Apache SOLR for indexing.
* Created a webpage using Bootstrap, Jquery, HTML5 and CSS to perform a query on the indexed tweets.
* Language translation api of Yandex was used to convert user input queries to multiple languages and then perform multi-lingual queries on Apache SOLR.
* Tweets were queried from Apache SOLR using Apache SOLR Rest api and displayed on the webpage based on the query provided by the user.

### Prerequisite:
* An Apache SOLR setup.
* Indexed database which can consist of tweets or any other dataset.

### Link to the main Code Files:
https://github.com/Sumedh0192/Multilingual-Tweet-Search-Engine/tree/master/HTMLPages
