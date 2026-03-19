# Contributing

Thanks for helping improve this DevOps learning path.

## Prerequisites

- Docker knowledge (required)
- kubectl installed and configured
- A local Kubernetes cluster (kind, minikube, or Docker Desktop)

## Workflow

1. Create a branch for your change
2. Add or update examples under `k8s/`
3. Keep manifests small and focused on the concept
4. Update `README.md` when you add or move topics

## Testing

Apply and remove your manifests in a local cluster:

```sh
kubectl apply -f <path>
kubectl delete -f <path>
```

## Security

- Do not commit secrets, kubeconfigs, or credentials
- Use placeholders for sensitive values

## Pull requests

- Fill out the pull request template
- Explain why the change helps learners
