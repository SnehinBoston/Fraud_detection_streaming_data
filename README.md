# Fraud_detection_streaming_data
Let’s assume we have company that offers a paid website service with about 10 Million daily accounts. There has been some reports of multiple people sharing the same account id and password and because of this fraudulent behavior the company is loosing a lot of money. The company wants to detect these fraudulent accounts in real time as they are happening. The company also wants to analyze the different actions performed by the users of these accounts such as click, purchase, login, log-out, delete-account, create-account, update-settings and other actions in real time.

I have used the following toolkit:
Apache Flink to perform computations over stream data.
Apache Kafka as a data source for streaming server-logs and alerts.
PostgreSQL database to store the user data.
Scala as the programming language.
