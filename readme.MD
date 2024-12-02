## Install Prometheus and node_exporter

```
Install Prometheus in /opt
create and start the prometheus.service which includes unit service and Install
[Unit]
Description=Prometheus
[Service]
ExecStart=/opt/prometheus/prometheus --config.file=/opt/prometheus/prometheus.yaml
[Install]
WantedBy=multi-user.target
