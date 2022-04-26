# docker-monitoring-stack

## Monitoring stack with CAdvisor Prometheus Grafana

The docker-compose.yml file provided in this repository will monitor the server where this docker file is deployed. Monitoring storing and previewing tools are also installed on the same server.

In production you should probably wish to speparate thes probes and the metrics storing tool and dashbord tools


### Probes to install on trarget servers:

* cadvisor - Docker instances monitor
* node_exporter - Server hardware monitoring

Probes can be deployed with the docker-compose-probe.yml file



