# Dash-OPS Helm Chart

## Introduction

This chart bootstraps a DashOps deployment on a Kubernetes cluster using the Helm Package manager.

## Installing the Chart

### Add Repository

```sh
helm repo add dash-ops https://charts.dash-ops.github.io
helm repo update
```

### Deploy

```sh
helm install --name dash-ops dash-ops/dash-ops
```

## Uninstalling the Chart

```sh
helm delete dash-ops
```
