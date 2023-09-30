Data Pipeline - AWS
the records of stock market were streamed through kafka and then stored into S3 which is then crawled by Glue crawler after every hour and updates the data catalog. the analytics on the table so-formed were carried out on Athena.


list of servies used:
1. Kafka (streaming)
2. S3 (staging)
3. Glue (orchestration)
4. Athena (analytics)