# searchEngine
A simlpe search engine to collect rss from blogs


#   TodoList
- Web spider to collect rss from blogs @delegete(Hua Haofeng)
- A simple search engine to search and store @delegete(Xu Shuo)
- Redis cache to buffer @deleget(Xu Shuo)
- Web Interface @delegete(Wang Wei)


# Structure

Web spider(Agent)-----> ETL(Filter extractor and Transformer) --------> Monogodb(Metadata) / Search Engine(Data Source and Indexr)<-------  Redis Cache(Cache Layer) <------- Service(Service Layer) <------ Resource(rest interface wrapper) <------ Web Interface

