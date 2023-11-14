# random-user-engineering

This project is a comprehensive end-to-end data engineering pipeline. It covers each stage from data ingestion to processing and finally to storage.

This project has the following component:
+ Used Python to extract data from the randomuser.me API and transform it
+ Orchestrated the pipeline using Apache Airflow and store fetched data in a PostgreSQL database
+ Used Apache Kafka and Zookeeper to stream data from PostgreSQL to the processing engine
+ Used Apache Spark for data processing with its master and worker nodes
+ Stored the processed data in Cassandra
+ Containerized everything using Docker for ease of deployment and scalability
