# wikipedia-state-manipulation

This analysis investigates how state actors manipulate information about other states on Wikipedia. 

State edits were retrieved according to state-owned or affiliated IP addresses. 

The majority of IP addresses were drawn from GitHub repositories focused on government transparency, including edsu/anon <https://github.com/edsu/anon> and jarib/anon-history.

18 Separately, some
countries, such as the United Kingdom, are required to list their IP address publicly by law. These
addresses were scraped from databases like RIPE NCC, the regional internet registry for Europe,
West Asia. All IP addresses, the country and organization to which they pertain, and their source,
are listed in the supplementary document ip list.csv.
In all, there are 24 countries and 3 international organizations represented in our sample:

Australia, Austria, Brazil, Canada, Chile, the European Commission of the European Union, Fin-
land, Germany, Ireland, Israel, Italy, NATO, Netherlands, New Zealand, Norway, Poland, Russia,

Sweden, Switzerland, Turkey, the United Kingdom, Ukraine, the United Nations, and the United
States.

The IP address 
Each step of the analysis has been separated out into separate notebooks. 
+ 1 retrieve_revid_by_ip: 
