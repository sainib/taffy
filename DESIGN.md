# Flow Designer - 

## Processing Options
* Text Mining 
* Segmentation 
* Entity Extraction 
* Sentiment Analysis
* Deep Linguistics 

## Ambari View - 

### Inputs
  - Ability to store categories and reuse categories
  - Configure End Points
  - Ingest Data 
   - How frequently 
   - Landing Directory 
   - Processing Hive Schema 
  - Identify Text
  - Identify other fields (including special fields like - review_rating -> this can be directly used in calculating customer sat, used in identifying product/service improvement opp.) 
  - Join fields 
  - Add Categories & Values 

### Processing 
  - Specify the type of processing 
  - Specify Frequency 
  
### Outout 
  - Solr 
  - HDFS
  - Hive


## Backend Setup 

### Overall Flow in Oozie  ( LATER ON NiFi ) 
  * Sqoop
  * HDFS commands
  * Hive Step 
  * Spark Step (One big scala/python app) 
  * Hive Step 
  * Shell Step (for Solr, HBase and/or Druid)
  * Zeppelin Notebook (samples per use case) 

## Development Steps 
  * Assume Generic Model
  * Ingest data 
  * Prep Data 
  * Run models
  * Spit output 


## Specific use case approach 
  * List domain specific use cases
  * Use case specific model 
  * Use case objectives  (Sentiment Analysis, CSAT, Product / Service Improvement Research, Investment / New Offering Opportunities, Targeted Ads - NBO/NBA) 
  * Use case outputs 
  
## Example View Widgets - 
* Overall Sentiment over the period of time (daily basis - by default) 
* Breakdown of Sentiment by categories - during selected period of time. 
* Change in sentiment over the period of time for all categories over the period of time. 
* Graphs to show sentiments for two factors on the chart? 

## TBD 
* Am i making use of row columnar format for making the storage generic? Or just create the hive tables and provide metadata externally.
* Joining can be done in Hive or Spark .. Spark if one of the inputs are file 
* 
