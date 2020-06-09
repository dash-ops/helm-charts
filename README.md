# Dash-OPS Helm Charts

![Release DashOps Charts](https://github.com/dash-ops/helm-charts/workflows/Release%20DashOps%20Charts/badge.svg)

## Introduction

This chart bootstraps a DashOps deployment on a Kubernetes cluster using the Helm Package manager.

## Installing the Chart

### Add Repository

```sh
helm repo add dash-ops https://dash-ops.github.io/helm-charts
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
