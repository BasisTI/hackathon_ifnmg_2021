# Hackathon online do IFNMG do Campus Arinos

## Desafio

## Como executar o projeto de exemplo

Para iniciar o Kafka

```
docker-compose up broker connect control-center schema_registry zookeeper
```

Para iniciar o Projeto de exemplo

```
docker-compose up hackathon-service
docker-compose up hackathon-client
```

Para iniciar a simulação da coleta de dados dos sensores:

```
./datagen-start.sh noise
```

Para parar a simulação da coleta de dados dos sensores:

```
./datagen-stop.sh noise
```
