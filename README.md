STARTUP HADOOP_______________________________________________________________

1. Open 3 terminal consoles

2. In 1st terminal 
   hdfs nodename

3. In 2nd terminal 
   hdfs datanode
______________________________________________________________________________

LOAD DATASET INTO HADOOP______________________________________________________

1. Create a directory for your dataset 
 hdfs dfs -mkdir user/DELL/<dataset_name>

2. Go to dataset dir

3. Put dataset into dfs directory 
   hdfs dfs -copyFromLocal data/set/path/<filename> /user/DELL/<dataset_name>

4. Start spark session 
   spark-shell
_______________________________________________________________________________

REMOVING A DIR_________________________________________________________________

hadoop fs -rm -r <HDFS_PATH>
_______________________________________________________________________________

