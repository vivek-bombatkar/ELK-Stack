# ELK-Stack
## 1. Theory
The ELK Stack is a collection of three open-source products — Elasticsearch, Logstash, and Kibana — from Elastic. 

E. Elasticsearch is a NoSQL database that is based on the Lucene search engine. 

L. Logstash is a log pipeline tool that accepts inputs from various sources, executes different transformations, and exports the data to various targets. 

K. Kibana is a visualization layer that works on top of Elasticsearch.

Elastic search concept 
Elasticsearch stores data as document / JSON (like rows in RDBMS)
document type  is like a table
index is like a database
shard - dived index over multiple chunks, distribute over nodes
cluster - collection of shard
replicas - copy of shards


## 2. Setup ELK on Windows 
https://logz.io/blog/installing-the-elk-stack-on-windows/

### 2.1 https://www.elastic.co/downloads/elasticsearch 

### 2.2 https://www.elastic.co/downloads/logstash

### 2.3 https://www.elastic.co/downloads/kibana


3. Running example
	a. https://logz.io/blog/windows-event-log-analysis/
	b. https://github.com/elastic/elasticsearch
4. TODO
	a. https://blog.webkid.io/visualize-datasets-with-elk/ - 30 min
https://howtodoinjava.com/microservices/elk-stack-tutorial-example/
