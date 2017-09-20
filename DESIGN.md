
Flow Designer - 

Ambari View - 

Inputs
  - Configure End Points
  - Ingest Data 
   - How frequently 
   - Landing Directory 
   - Processing Hive Schema 
  - Identify Text
  - Identify other fields 
  - Join fields 
  - Add Categories & Values 

Processing 
  - Specify the type of processing 
  - Specify Frequency 
  
Outout 
  - Solr 
  - HDFS
  - Hive


Backend Setup 

** Overall Flow 

Oozie  ( LATER ON NiFi ) 
  - Sqoop
  - HDFS commands
  - Hive Step 
  - Spark Step (One big scala/python app) 
  - Hive Step 
  - Shell Step (for Solr and/or Druid) 
  - Zeppelin Notebook (samples per use case) 

Development Steps 
  - Assume Generic Model
  - Ingest data 
  - Prep Data 
  - Run models
  - Spit output 


Specific use case approach 
  - List domain specific use cases
  - Use case specific model 
  - Use case objectives 
  - Use case outputs 

