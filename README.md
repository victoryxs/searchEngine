# searchEngine
Edit a simlpe search engine to collect rss from blogs


#   TodoList
- Web spider to collect rss from blogs @delegete(Hua Haofeng)
- A simple search engine to search and store @delegete(Xu Shuo)
- Redis cache to buffer @deleget(Xu Shuo)
- Web Interface @delegete(Wang Wei)


# Structure

Monogodb(Metadata) <-----------------------------------------------

Web spider(collect agent)-----> ETL(data filter and transform) --------> Search Engine(data source and indexr)<-------  Redis Cache(cache) <------- Service(some service) <------ Resource(rest interface wrapper) <------ Web Interface

