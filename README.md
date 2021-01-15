# Hackathon online do IFNMG do Campus Arinos

## Desafio

## Como executar o projeto de exemplo

Para iniciar o Kafka

```
docker-composer up broker connect control-center schema_registry zookeeper
```

Para iniciar o Projeto de exemplo

```
docker-composer up hackathon-service
docker-composer up hackathon-client
```

Para iniciar a simulação da coleta de dados dos sensores:

```
./datagen-start.sh noise
```

Para parar a simulação da coleta de dados dos sensores:

```
./datagen-stop.sh noise
```
