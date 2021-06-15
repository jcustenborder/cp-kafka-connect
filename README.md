# Introduction

This project provides an example Dockerfile that is used to extend the [confluentinc/cp-kafka-connect](https://hub.docker.com/r/confluentinc/cp-kafka-connect) docker image. Creating a standard docker image is a common way to deploy Kafka Connect workers. Please note the content in this repository is generated based on a build script. Any pull requests should go against [jcustenborder/kafka-connect-docker](https://github.com/jcustenborder/kafka-connect-docker) instead.

| Plugin | Version | Documentation | Source |
|--------|---------|---------------|--------|
| [C0urante/kafka-connect-reddit](https://www.confluent.io/hub/C0urante/kafka-connect-reddit) | 0.1.3 | [Documentation](https://github.com/C0urante/kafka-connect-reddit) | [Source](https://github.com/C0urante/kafka-connect-reddit) |
| [confluentinc/kafka-connect-activemq](https://www.confluent.io/hub/confluentinc/kafka-connect-activemq) | 11.0.7 | [Documentation](https://docs.confluent.io/kafka-connect-activemq-source/current/index.html) | [Source](None) |
| [confluentinc/kafka-connect-activemq-sink](https://www.confluent.io/hub/confluentinc/kafka-connect-activemq-sink) | 1.3.2 | [Documentation](https://docs.confluent.io/current/connect/kafka-connect-activemq/sink) | [Source](None) |
| [confluentinc/kafka-connect-datagen](https://www.confluent.io/hub/confluentinc/kafka-connect-datagen) | 0.5.0 | [Documentation](https://github.com/confluentinc/kafka-connect-datagen/blob/master/README.md) | [Source](https://github.com/confluentinc/kafka-connect-datagen) |
| [confluentinc/kafka-connect-ibmmq](https://www.confluent.io/hub/confluentinc/kafka-connect-ibmmq) | 11.0.7 | [Documentation](https://docs.confluent.io/kafka-connect-ibmmq-source/current/) | [Source](None) |
| [confluentinc/kafka-connect-ibmmq-sink](https://www.confluent.io/hub/confluentinc/kafka-connect-ibmmq-sink) | 1.3.2 | [Documentation](https://docs.confluent.io/current/connect/kafka-connect-ibmmq/sink) | [Source](None) |
| [debezium/debezium-connector-mysql](https://www.confluent.io/hub/debezium/debezium-connector-mysql) | 1.5.0 | [Documentation](http://debezium.io/docs/connectors/mysql/) | [Source](https://github.com/debezium/debezium/) |
| [jcustenborder/kafka-config-provider-aws](https://www.confluent.io/hub/jcustenborder/kafka-config-provider-aws) | 0.1.1 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/projects/kafka-config-provider-aws/) | [Source](https://github.com/jcustenborder/kafka-config-provider-aws) |
| [jcustenborder/kafka-config-provider-azure](https://www.confluent.io/hub/jcustenborder/kafka-config-provider-azure) | 0.1.2 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/projects/kafka-config-provider-azure/) | [Source](https://github.com/jcustenborder/kafka-config-provider-azure) |
| [jcustenborder/kafka-config-provider-gcloud](https://www.confluent.io/hub/jcustenborder/kafka-config-provider-gcloud) | 0.1.1 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/projects/kafka-config-provider-gcloud/) | [Source](https://github.com/jcustenborder/kafka-config-provider-gcloud) |
| [jcustenborder/kafka-config-provider-vault](https://www.confluent.io/hub/jcustenborder/kafka-config-provider-vault) | 0.1.2 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/projects/kafka-config-provider-vault/) | [Source](https://github.com/jcustenborder/kafka-config-provider-vault) |
| [jcustenborder/kafka-connect-aerospike](https://www.confluent.io/hub/jcustenborder/kafka-connect-aerospike) | 0.2.4 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/projects/kafka-connect-aerospike/index.html) | [Source](https://github.com/jcustenborder/kafka-connect-aerospike) |
| [jcustenborder/kafka-connect-email](https://www.confluent.io/hub/jcustenborder/kafka-connect-email) | 0.1.0.2 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-email) |
| [jcustenborder/kafka-connect-flume-avro](https://www.confluent.io/hub/jcustenborder/kafka-connect-flume-avro) | 0.2.8 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-flume-avro) |
| [jcustenborder/kafka-connect-json-schema](https://www.confluent.io/hub/jcustenborder/kafka-connect-json-schema) | 0.2.5 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-json-schema) |
| [jcustenborder/kafka-connect-memcached](https://www.confluent.io/hub/jcustenborder/kafka-connect-memcached) | 0.1.0.12 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-memcached) |
| [jcustenborder/kafka-connect-opentsdb](https://www.confluent.io/hub/jcustenborder/kafka-connect-opentsdb) | 0.1.2 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-opentsdb) |
| [jcustenborder/kafka-connect-redis](https://www.confluent.io/hub/jcustenborder/kafka-connect-redis) | 0.0.2.12 | [Documentation](https://docs.confluent.io/current/connect/kafka-connect-redis/) | [Source](https://github.com/jcustenborder/kafka-connect-redis) |
| [jcustenborder/kafka-connect-simulator](https://www.confluent.io/hub/jcustenborder/kafka-connect-simulator) | 0.1.120 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-simulator) |
| [jcustenborder/kafka-connect-solr](https://www.confluent.io/hub/jcustenborder/kafka-connect-solr) | 0.1.39 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-solr) |
| [jcustenborder/kafka-connect-spooldir](https://www.confluent.io/hub/jcustenborder/kafka-connect-spooldir) | 2.0.62 | [Documentation](https://docs.confluent.io/kafka-connect-spooldir/current/index.html) | [Source](https://github.com/jcustenborder/kafka-connect-spooldir) |
| [jcustenborder/kafka-connect-transform-cobol](https://www.confluent.io/hub/jcustenborder/kafka-connect-transform-cobol) | 0.1.0.1 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/projects/kafka-connect-transform-cobol) | [Source](https://github.com/jcustenborder/kafka-connect-transform-cobol) |
| [jcustenborder/kafka-connect-transform-common](https://www.confluent.io/hub/jcustenborder/kafka-connect-transform-common) | 0.1.0.54 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-transform-common) |
| [jcustenborder/kafka-connect-transform-fix](https://www.confluent.io/hub/jcustenborder/kafka-connect-transform-fix) | 0.1.0.1 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-transform-fix) |
| [jcustenborder/kafka-connect-transform-maxmind](https://www.confluent.io/hub/jcustenborder/kafka-connect-transform-maxmind) | 0.1.0.10 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-transform-maxmind) |
| [jcustenborder/kafka-connect-transform-xml](https://www.confluent.io/hub/jcustenborder/kafka-connect-transform-xml) | 0.1.0.20 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/projects/kafka-connect-transform-xml/) | [Source](https://github.com/jcustenborder/kafka-connect-transform-xml) |
| [jcustenborder/kafka-connect-twitter](https://www.confluent.io/hub/jcustenborder/kafka-connect-twitter) | 0.3.33 | [Documentation](https://jcustenborder.github.io/kafka-connect-documentation/) | [Source](https://github.com/jcustenborder/kafka-connect-twitter) |
