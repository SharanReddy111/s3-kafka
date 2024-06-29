FROM confluentinc/cp-kafka-connect-base:7.6.1

COPY target/kafka-s3-sink-connector-1.0-SNAPSHOT.jar /usr/share/java/kafka-connect-s3/

ENV CONNECT_PLUGIN_PATH="/usr/share/java/kafka-connect-s3"
