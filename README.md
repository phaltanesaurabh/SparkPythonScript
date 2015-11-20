Spark Script is submitted to sparksubmit for processing exectes as follows:
1)Connecting with Elasticsearch retrieving data ,
2)Running Map Reduce Functions, 
3)Calculating the Unique IP addresses and Unique Log Messages .
4)reduced results back to Elasticsearch.

The haddop elasticsearch Connector is used for interfacing spark and Elasticsearch.

The Spark Scrip indexes the reduced results back to Elasticsearch other index.

The script is work in progress for developing Advanced analytics for aggregated logs in elasticsearch for CMPE 272 Project.