# kubernetes-kind

Docs: https://kind.sigs.k8s.io/docs/user/quick-start/

## Setup Kind, Kubectl and the cluster

```bash
chmod +x ./setup.sh && ./setup.sh
```

## Manually launch the cluster
```bash
kind create cluster --config ./kind-cluster-3master-3workers.yml
```

## Delete the cluster

```bash
kind delete cluster
```