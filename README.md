# Docker Kafka
Builds a docker image for Kafka.

## Summary

Repository name in Docker Hub: [aviata/kafka](https://hub.docker.com/u/aviata/kafka)

This repository contains Dockerized Kafka, published to the public Docker Hub via *automated build*.

## Usage

```docker run -p 9092:9092 aviata/kafka```

## Build
``` docker build -t aviata/kafka . ```

## Dependencies

stackbrew/ubuntu:14.04
