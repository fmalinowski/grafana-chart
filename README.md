# Grafana dashboards

This repository contains a collection of Grafana dashboards I made to monitor Kubernetes clusters.
They fit my own needs but you're welcome to use them too. Just do not claim them as your own ones.

Here are the Grafana dashboards listed in this repository:

- `kubernetes-metrics-dashboard.json`

    This dashboard is used to display some of the main metrics of a Kubernetes cluster (CPU, Memory, Network traffic, etc.).
    They contain also 2 sections (backend) that use custom Prometheus metrics to monitor some backend containers I developed (those containers are not available publicly).
