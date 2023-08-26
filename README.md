# OpenTelemetryInfra

## Prérequis
docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions

## Exécution
docker-compose up / down

## Résultat
Installation des éléments d'infrastructures suivants :
- Prometheus
- Loki
- Tempo
- Grafana
- Redis
- RabbitMQ

Les sources données suivantes sont configurées :
- Prometheus
- Loki
- Tempo

Les tableaux de bord suivants sont configurés dans Grafana :
- ASP.NET OTEL (OpenTelemetry) Metrics
- Loki2.0 Global Metrics
- Prometheus 2.0 Overview
- RabbitMQ-Overview
- Redis Dashboard for Prometheus Redis Exporter 1.x