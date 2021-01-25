# Hackathon online do IFNMG do Campus Arinos

## Desafio

O desafio pode ser acessado no seguinte [endereço](desafio/desafio-iot-ifnmg-basis.md).

## Docker

Para snstalar o docker engine [instruções](https://docs.docker.com/engine/install/).

PAra instalar o docker compose seguir as [instruções](https://docs.docker.com/compose/install/).

## Projeto de exemplo

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

Pode-se optar pelo uso de json na coleta de dados dos sensores:

```
./datagen-start.sh noise-json
```

Para parar a simulação da coleta de dados dos sensores em json:

```
./datagen-stop.sh noise-json
```
