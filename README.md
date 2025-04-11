## Observability

This project includes the following observability services from the Grafana Stack: 
  - Promtail: Log collector and shipper. Reads log files and sends them to Loki
  - Loki: Log storage and query engine. Stores logs received from Promtail and makes them searchable.
  - Prometheus: Metrics collector and time-series database. Scrapes metrics from instrumented services.
  - Tempo: For distributed tracing. Collects and stores traces of requests as they flow through microservices.
  - Grafana: Unified visualization and dashboard platform. Displays data from Loki, Prometheus, and Tempo in one place.

To run this project all you need to do is run `docker-compose up -d` in your terminal.
