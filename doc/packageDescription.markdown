# Package Description

## searchEngine-agent module

This module is for web spider for collecting rss info from network. And the module belongs to @HuaHaofeng. Inside the module, how to allocate package depends on your mind. 

## searchEngine-core module

This module is for searchEngine Server to handle the info from message queue and display the result from web-interface. And the module belongs to @victoryxs and @WangWei. 

Inside the module

### searchEngine-server module

This module contains jetty server resource layer and web-app, @WangWei develop in this module.

### searchEngine-cache module

This module contains redis cache to buffer.

### searchEngine-datastore module

This module contains mongodb to store the metadata.

### searchEngine-engine module

This module contains searchEngine to index and store the data and manage the input from output.

### searchEngine-model module

This module contains searchEngine to define model layer.

### searchEngine-service module

This module contains searchEngine to define service layer.

### searchEngine-plugins module

This module contains some implements of input and output.

### searchEngine-util module

This module contains some common method and parsing progress about config.yaml  

## searchEngine-dist module

This module tar the project.