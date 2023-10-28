# Realtime-Data-Streaming-End-to-End-Data-Engineering-Project
This project serves building an end-to-end data engineering pipeline. It covers each stage from data ingestion to processing and finally to storage, utilizing a robust tech stack that includes Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark, and Cassandra. Everything is containerized using Docker for ease of deployment and scalability.

# System Architecture
![Data Engineering Architecture](/Data%20engineering%20architecture.png)

# The project is designed with the following components:

<ul dir="auto">
<li><strong>Data Source</strong>: We use <code>randomuser.me</code> API to generate random user data for our pipeline.</li>
<li><strong>Apache Airflow</strong>: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.</li>
<li><strong>Apache Kafka and Zookeeper</strong>: Used for streaming data from PostgreSQL to the processing engine.</li>
<li><strong>Control Center and Schema Registry</strong>: Helps in monitoring and schema management of our Kafka streams.</li>
<li><strong>Apache Spark</strong>: For data processing with its master and worker nodes.</li>
<li><strong>Cassandra</strong>: Where the processed data will be stored.</li>
</ul>

# Technologies
<ul dir="auto">
<li>Apache Airflow</li>
<li>Python</li>
<li>Apache Kafka</li>
<li>Apache Zookeeper</li>
<li>Apache Spark</li>
<li>Cassandra</li>
<li>PostgreSQL</li>
<li>Docker</li>
</ul>
