# searchEngine
topic: edit a simlpe search engine to collect rss from blogs


#   TodoList
- Web spider to collect rss from blogs @delegete(Hua Haofeng)
- A simple search engine to search and store @delegete(Xu Shuo)
- Redis cache to buffer @deleget(Xu Shuo)
- Web Interface @delegete(Wang Wei)


# Structure

Monogodb <-----------------------------------------------

Web spider-----> ETL --------> Search Engin <-------  Redis Cache  <------- Service <------ Resource <----- REST API <------ Web Interface

