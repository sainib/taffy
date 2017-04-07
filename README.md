# taffy
Text Analytics Framework For Your hadoop

# Overview
The idea is to have a framework to speed up building the text analytics on Hadoop. The framework would support generalized text analytics models but will be extensible by plugging in sources for data, new models and steps in processing and providing metadata for richer context for text analytics. 

# Architecture 

## Data Flow 

<img src="https://raw.githubusercontent.com/sainib/taffy/master/flow.png">

## Tools 

### Supported Source 
* Databases, including Hive
* Web sources (Forums, Social Media, Website using Crawler) 
* Email Sources
* Docs (Excel, Word, PDF, CSV/Text etc) 
* Images may be for Image Analytics and association with text?

### Ingestion 
* NiFi 

### Analytics Processing for all stages 
* Hive (using UDFs) 
* Python
* Spark
* Java NLP
* Other open source NLP platforms

### Consumption Layer
* Solr + BananaUI 
* Hive 
* HBase 
* Zeppelin notebooks 
* Superset
 
### Admin Layer 
* Ambari View to configure the process

# Extensibility 

* Hooks to add on processing 
