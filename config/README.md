
## Contents
- [Zookeeper Configuration](#zookeeper-configuration)
- [Kafka Broker Configuration](#kafka-broker-configuration)
- [Topics Creation](#topics-creation)
- [Consumers and Producers](#consumers-and-producers)
- [Submission Files](#submission-files)

## Zookeeper Configuration
- **File**: `config/zookeeper.properties`
- **Description**: Configuration file for the Zookeeper server.

## Kafka Broker Configuration
- **Files**:
  - `config/server1.properties`
  - `config/server2.properties`
  - `config/server3.properties`
- **Description**: Configuration files for the Kafka brokers.

## Topics Creation
- **Topics**:
  - `test1` with 3 partitions
  - `test2` with 2 partitions
- **Description**: Creation of Kafka topics with specified partitions and replication factors.

## Consumers and Producers
- **Consumers**:
  - Console consumers for `test1` topic
  - Console consumers with consumer group `group1` for `test1` topic
- **Producers**:
  - Console producer for `test1` topic
  - Console producer with key-value pairs for `test1` topic

## Submission Files
- **commands.pdf**: Document containing commands used in each step and answers to the questions.
- **config.zip**: Zip file containing configuration files used for the assignment.
