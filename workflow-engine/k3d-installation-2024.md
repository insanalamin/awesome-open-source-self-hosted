# Workflow Engine K3d Installation - 2024

## N8N

### Install Using Custom YAML

Applying the resource
```sh
kubectl apply -f n8n-timescaledb-namespace.yaml
```

Port forwarding (if you want to access the node from port 5678)
```sh
kubectl port-forward svc/n8n -n n8n-insan 5678:80
```

## Prefect

### Install Prefect Server
```sh
helm repo add prefecthq https://prefecthq.github.io/server/
helm repo update
helm install prefect-server prefecthq/prefect-server
```

### Install Prefect Client

### Install Prefect Agent
