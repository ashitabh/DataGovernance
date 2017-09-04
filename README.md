# Data Governance with Hortonworks HDP
Hortonworks created an Apache Hadoop Data Governance Initiative to address the need for open source governance solution to manage data classification, data lineage, security and data lifecycle management.
Apache Atlas, created as part of the Hadoop data governance initiative, empowers organizations to apply consistent data classification across the data ecosystem. Apache Ranger provides centralized security administration for Hadoop. By integrating Atlas with Ranger, Hortonworks empowers enterprises to institute dynamic access policies at run time that proactively prevents violations from occurring.
![alt text](https://2xbbhjxc6wk3v21p62t8n4d4-wpengine.netdna-ssl.com/wp-content/uploads/2016/04/next_gen_hadoop_security_diagram_horizontal.png)

Effective steps for implementing security on hadoop
1. Setup Kerberos
2. Setup centralized policies in Ranger
3. Setup column levelk security for Hive and Hbase
4. Centralize logging 
5. Encrypt sensitive data
6. Data lineage via Atlas
7. Standardize data integration pattern 
  a.Apache storm for streaming data
  b.Apache spark for batch data ( Scheduled via Falcon)
  
