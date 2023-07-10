# rabbitmq quorum queue example

this repo contains docker compose project to create rabbitmq cluster with 3 nodes and go samples to send and receive messages using the created cluster.

## install dependencies

- docker and docker-compose
- go1.20.4

## create the cluster

docker-compose up -d

## send message

go run send/send.go

## receive message

from another terminal:
go run receive/receive.go
