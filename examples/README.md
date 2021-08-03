# Azure HDInsight Terraform Module

Terraform module to create managed, full-spectrum, open-source analytics service Azure HDInsight. This module creates Hadoop, Apache Spark, Apache HBase, Interactive Query (Apache Hive LLAP) and Apache Kafka clusters.

## Module Usage

* [Hdinsight Hadoop Cluster](examples/hdinsight_hadoop_cluster/README.md)
* [Hdinsight HBase Cluster](examples/hdinsight_hbase_cluster/README.md)
* [Hdinsight Interactive Query Cluster](examples/hdinsight_interactive_query_cluster/README.md)
* [Hdinsight Kafka Cluster](examples/hdinsight_kafka_cluster/README.md)
* [Hdinsight Spark Cluster](examples/hdinsight_spark_cluster/README.md)

## Terraform Usage

To run this example you need to execute following Terraform commands

```hcl
terraform init
terraform plan
terraform apply
```

Run `terraform destroy` when you don't need these resources.