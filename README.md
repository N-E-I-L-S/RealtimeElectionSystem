# REALTIME ELECTION SYSTEM
The project utilises python, kafka broker, pyspark and spark streaming. The GUI is built using streamlit.

## System Design
![alt text](https://github.com/N-E-I-L-S/RealtimeElectionSystem/blob/master/images/Group%2031%20(1).svg)
## REQUIREMENTS and PATHS:
- HADOOP_HOME -- get winutils and .dll file for hadoop on windows
- JAVA_HOME
- PYSPARK_HOME
- SPARK_HOME

## VERSIONS USED:
- spark - 3.5.1
- scala - 2.12.18
- kafka - 3.7.0
- java - 21.0.1
- python - 3.11.4 
- postgres - 16.1

## ADDITIONAL JARS:
- postgresql-42.7.1.jar
- spark-sql-kafka-0-10_2.12-3.5.1.jar

## COMMANDS:
+ kafka-zookeper run command:

.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

+ kafka-server run command:
  
.\bin\windows\kafka-server-start.bat .\config\server.properties

+ spark-master run command:

spark-class org.apache.spark.deploy.master.Master

+ spark-worker run command:
  
spark-class org.apache.spark.deploy.worker.Worker spark://<SPARK-MASTER-IP>:7077


## Postgres config: (set in code)
- username: 
- password:
