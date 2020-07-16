# Retail-Data-Engineering-and-Analytics
Building of this Data lake project provides an all in one central repository for converged Data Platform that helps
retailers chain of stores to integrate and analyze a wide variety of online and offline customer data including the
customer data, products, purchases, orders, employees and comments data. Retailers can analyze this data to
generate insights about individual consumer behaviors and preferences, Recommendations and Loyalty Programs. 
## Getting Started
 - Install VMware 15 player 
 - Install centos
 - Install requirements
 - Start Services
 - Run the scripts
## Local Installation
Install tools given in `requirements.txt` and also refer to `conf` above for configuration.

**Make sure you have the following installed:**
- Hadoop
- Sqoop
- Hive
- Hbase
- Phoenix
- Zookeeper

**Installing mysql & postgresql**
- [mysql](https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-centos-7).
- [postgresql](https://linuxize.com/post/how-to-install-postgresql-on-centos-7/).
## Starting services 
- Hadoop
  - start-all.sh 
  - mr-jobhistory-daemon.sh start historyserver (job history server)
- Mysql service
  - service mysqld start
- Hive metastore in a terminal
  - hive --service metastore & (as background service)
- Hbase
  - start-hbase.sh 
- Zookeeper
  - zkServer.sh start
- Phoenix
  - sqlline.py localhost
## Run the scripts
   Generate reports from the final table
