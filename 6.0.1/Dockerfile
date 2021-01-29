FROM confluentinc/cp-kafka-connect:6.0.1-1-ubi8
LABEL maintainer="Jeremy Custenborder jcustenborder@gmail.com"
ENV CONNECT_PLUGIN_PATH=/usr/share/java,/usr/share/confluent-hub-components
RUN confluent-hub install --no-prompt C0urante/kafka-connect-reddit:0.1.2
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-activemq:10.1.0
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-activemq-sink:1.1.6
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-datagen:0.4.0
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-ibmmq:10.1.0
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-ibmmq-sink:1.3.1
RUN confluent-hub install --no-prompt debezium/debezium-connector-mysql:1.3.1
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-aerospike:0.2.4
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-email:0.1.0.2
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-flume-avro:0.2.8
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-json-schema:0.2.5
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-memcached:0.1.0.12
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-opentsdb:0.1.2
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-redis:0.0.2.11
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-simulator:0.1.120
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-solr:0.1.35
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-spooldir:2.0.58
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-transform-cobol:0.1.0.1
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-transform-common:0.1.0.39
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-transform-fix:0.1.0.1
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-transform-maxmind:0.1.0.10
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-transform-xml:0.1.0.20
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-twitter:0.3.33
