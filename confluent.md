# The neccessary Command for confluent

### Donload Link: ``` https://www.confluent.io/blog/set-up-and-run-kafka-on-windows-and-wsl-2/ ```

### Path Variable Setup:
    ``` export CONFLUENT_HOME=~/confluent-6.1.0
        export PATH="confluent-6.1.0/bin:$PATH" ```
   
### Plagin: 
```confluent-hub install --no-prompt confluentinc/kafka-connect-jdbc:10.5.0
confluent-hub install --no-prompt mongodb/kafka-connect-mongodb:1.7.0
confluent-hub install --no-prompt debezium/debezium-connector-mysql:1.9.2
confluent-hub install --no-prompt confluentinc/kafka-connect-json-schema-converter:7.1.1
confluent-hub install --no-prompt confluentinc/kafka-connect-elasticsearch:13.0.0 ```
