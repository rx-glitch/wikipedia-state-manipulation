# wikipedia-state-manipulation

This analysis investigates how state actors manipulate information about other states on Wikipedia. 

State edits were retrieved according to state-owned or affiliated IP addresses, based on data available in Wikimedia's online dumps repository as at December 5, 2020. In all, there are 24 countries and 3 international organizations represented in our sample: Australia, Austria, Brazil, Canada, Chile, the European Commission of the European Union, Finland, Germany, Ireland, Israel, Italy, NATO, Netherlands, New Zealand, Norway, Poland, Russia, Sweden, Switzerland, Turkey, the United Kingdom, Ukraine, the United Nations, and the United States.

Each step of the analysis (after IP address compilation) has been separated out into separate notebooks. 
+ *1_retrieve_revid_by_ip*: Takes Wikimedia's XML dump files and retrieves revision IDs corresponding to the list of relevant IP addresses.
+ *2_retrieve_content*: Queries the Wikipedia API to retrieve the contents of the pages edited by revision ID.
+ *3_prepare_corpus*: Prepares corpus of documents for topic modelling.
+ *4_topic_model_article*: LDA topic modelling on the full Wikipedia articles.
+ *4_topic_model_edits*: LDA topic modelling on just the content of the edits.
+ *5_cross_country_mentions*: Creates adjacency matrix of mentions between countries.
+ *5_cross_country_mentions_heatmap*: Visualizes cross-country mentions into heatmap.
