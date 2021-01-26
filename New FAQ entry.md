# Algolia Ranking vs. ElasticSearch Ranking
Algolia has a special ranking method, and with it, your Algolia search engine can be up and running on your website very quickly.



## Algolia Ranking - tie-breaking approach
The tie-breaking approach focuses on searching a database. 

At Algolia we have our own ranking method for matching records. We recommend a specific criterion in a specific order. We also offer custom ranking, which works alongside Algolia ranking to give more attention to the products that you want to call out.

Algolia uses a tie-breaking approach. Specific details of each criterion are analyzed, and the best matches are shown in the search results. Algolia reuses this data for future searches to better the search experience.



## Elastic Ranking - tf-idf approach
The tf-idf approach focuses on searching a document.

Elastic Search is defined by frequency. Depending on how often a search term appears in a result, the relevancy is determined. Elastic Search can cover large expanses of data including worldwide connections. 

Elastic Search covers all ranges of applications. A lot of engneering power is needed to create a successful Elastic Search experience.



## When to use which

#### Use Algolia when

* You need your search engine distributed quickly

* You need your search engine to work across regions

* You need a search engine that is is guaranteed to be fast

* You don't have a large team to work on your search engine

#### Use Elastic when

* You need your search to focus on a large amounts of documents at one time

* You need your search to collect data for a trasaction log

* You need your search to run specific inquiries

* You need your search to run complex groups of data
