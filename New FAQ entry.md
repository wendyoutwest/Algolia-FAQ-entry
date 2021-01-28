# Algolia Ranking vs. ElasticSearch Ranking
Algolia has a special ranking method, and with it, your Algolia search engine can be up and running on your website very quickly.



## Algolia Ranking - tie-breaking approach
The tie-breaking approach focuses on searching a database.

At Algolia, we have our own ranking method for matching records. We recommend a specific criterion in a specific order. We also offer custom ranking, which works alongside Algolia ranking to give more attention to the products that you want to highlight.

Algolia uses a tie-breaking approach. Specific details of each of the criterion are analyzed. All matches for the first criterion are sorted and scored. Any results with scores that are tie are matched again, this time with the second criterion. This continues for each criterion, and the outcome is shown in the final search results.

Algolia reuses this data for future searches to better the overall search experience.



## Elastic Ranking - tf-idf approach
The tf-idf approach focuses on searching documents.

Elastic Search is defined by frequency. Depending on how often a search term appears in a result, the term's relevancy is determined. A tf-idf approach ranks a term's significance based on the number of times it appears, which determines the importance of that term. The importance is also measured against the number of documents in which a term appears in order to note which terms appear more frequently in general.

Elastic Search can cover all ranges of applications and large expanses of data including worldwide connections. A lot of engineering power is needed to create a successful Elastic Search experience.



## When to use which

#### Use Algolia when

* You need your search engine distributed quickly
* You need your search to work across regions
* You want your search to be customized for your data
* You need a search that is guaranteed to be fast
* You don't have a large team to work on your search engine


#### Use Elastic when

* You need your search engine to focus on large amounts of documents at one time
* You need your search to collect data for a transaction log
* You need your search to run specific inquiries
* You need your search to run complex groups of data
* You have the available personnel to maintain your search engine
