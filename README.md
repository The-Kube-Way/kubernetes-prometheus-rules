# kubernetes-prometheus-rules

[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

This project aims to provide useful [Prometheus rules](https://prometheus.io/docs/prometheus/latest/configuration/alerting_rules/) for Kubernetes ecosystem.

## Usage

Manifests can be cloned or the latest version can be directly used using Kustomize:

```yaml
apiVersion: kustomize.config.k8s.io/v1beta1
kind: Kustomization
resources:
- https://raw.githubusercontent.com/The-Kube-Way/kubernetes-prometheus-rules/main/rules/prometheus.yaml
- [...]
```

## Contribution

Pull-Requests are welcome!
