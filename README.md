# Docker Coin Helm Chart

This is a Helm chart for Docker Coin, a sample application used to demonstrate Docker Enterprise Edition features.

## Prerequisites

```bash
helm install dockercoin . --namespace dockercoin
```

## Rollout

```bash
helm upgrade dockercoin . --namespace dockercoin
```

## Rollback

```bash
helm rollback dockercoin 1 --namespace dockercoin
```