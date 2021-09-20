# flink-sql-demo-redpanda
End-to-End Demo with Flink, Redpanda, MySQL, Elastic, and Kibana

Based on https://github.com/wuchong/flink-sql-demo.

This modifies the original project to use Redpanda in place of Kafka. To run the demo:

```
mkdir flink-sql-demo-redpanda; cd flink-sql-demo-redpanda
wget https://raw.githubusercontent.com/patrickangeles/flink-sql-demo-redpanda/main/docker-compose.yml
```

Apart from this detail, follow the rest of the instructions as per the blog
https://flink.apache.org/2020/07/28/flink-sql-demo-building-e2e-streaming-application.html
with no other modifications.
