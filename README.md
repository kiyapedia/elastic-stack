# Dockerized Elastic Stack

## Introduction

The Elastic Stack was developed by [Elastic](https://www.elastic.co/) and is arguably the most popular, Open-Source, log management platform today. It consists of Elasticsearch and Kibana.

- Elasticsearch is a RESTful search and analytics engine which centrally stores your data
- Kibana lets you visualize your Elasticsearch data

## Purpose

This repository consists of a configured dockerized instance of the Elastic Stack.

## Prerequisites

- Some knowledge of Docker
    - Learn more [here](https://docs.docker.com/get-started/)
- Docker installed
    - Install Docker on a Mac [here](https://docs.docker.com/docker-for-mac/install/)
    - Install Docker on Windows [here](https://docs.docker.com/docker-for-windows/install/)
- 4.0 GB of memory allocated to docker
    - Docker Preferences > Resources > Advanced

## Bringing up the Elastic Stack

- Clone this repo
- `cd` into the root of the directory
- Run `docker-compose up`
- Visit `localhost:9200` to view Elasticsearch
- Visit `localhost:5601` to view Kibana

## Elastic Stack series

Be sure to checkout my Elastic Stack series on my [Dev blog](https://dev.to/kiyapedia) to learn how you can:
- Secure your dockerized Elastic Stack
- Ship logs to your dockerized Elastic stack
- Query and visualize your logs
- Alert based off of your logs
- Deploy your dockerized Elastic Stack to production
