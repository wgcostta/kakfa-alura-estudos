### kakfa-alura-estudos

bin/zookeeper-server-start.sh config/zookeeper.properties
bin/kakfa-server-start.sh config/server.properties

bin/kafka-consumer-groups.sh --all-groups --bootstrap-server localhost:9092 --describe