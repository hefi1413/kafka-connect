### Links úteis

- [Kafka Control Center](http://localhost:9021/)
- [Mongo Express](http://localhost:8085/)

### Informações

Estou tentando utilizar o conector Postgresql com o kafka-connect.

Já atualizei o docker-compose.yaml e verifiquei com o comando "ls" que o conector foi instalado no diretorio: /usr/share/confluent-hub-components

Contudo, quando pesquiso com o comando curl -s http://localhost:8083/connector-plugins o conector Postgresql não aparece. E quando tentado fazer o upload no site da confluent control center (http://localhost:9021/) o site informa que a classe é inválida. (parece que não reconhece a instalação) 

No site da Debezium Postgresql informa que o conector debezium/debezium-connector-postgresql:3.1.2 está "deprecated" 
