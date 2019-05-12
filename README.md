# Auto ingestion from MySQL to Hive

The increase in large amounts of data is generated incessantly thus industries encounter difficulties. MySQL 
is one of the main databases from which data are injected into Hive. Automatic input is performed to update 
data in the Hive database when any information is entered in MySQL. Sqoop is designed to efficiently 
transfer large amounts of data between the Apache Hive and structured data storages, such as relational 
databases. It is highly efficient in performing data injection operations. Hive is much faster in its 
performance and also supports scale for data analysis. Sqoop is built in scala and is effective when 
performing operations in the Hive. The data from the sensor is fetched using WiFi module i.e., NodeMCU. 
Data is sent to MySQL through the cloud. Automatic import of data into MySQL is done via Sqoop. The 
proposed system is a self-updating system. Any changes made to the MySQL database are reflected in the 
Hive database. The Apache Sqoop tool is designed to efficiently transfer mass data between Hadoop and 
structured data storage. The update or insertion in the MySQL table is performed through Python code. If a 
change is detected in the MySQL table, the Sqoop job is called which updates the data in Hdfs. The Python 
code performs the logic for entering the updated data from MySQL to Hive. This program works 
consistently by updating data every second. Sqoop uses the map reduce algorithm internally which imports 
data and distributes them into cluster. There are several parameters that you can specify for a Sqoop 
command that offers better control in storing, managing and analyzing data. The database systems that are 
normally used are not sufficient to handle such large data. Thus data is stored and processed efficiently in 
Hive.
