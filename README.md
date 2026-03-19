# DevOps Learning Path

A practical, incremental learning path for DevOps fundamentals.
Start with Kubernetes basics, move into Terraform, and round out with Docker fundamentals.

## Path overview

1. Kubernetes basics (current)
   - Namespaces
   - Pods
2. Terraform basics (planned)
3. Docker fundamentals (planned)

## Repository structure

- `k8s/basic/Namespace/` - Kubernetes namespace examples
- `k8s/basic/Pod/` - Kubernetes pod examples
- `k8s/kind-bind-mount-1/` - Kind bind-mount example 1
- `k8s/kind-bind-mount-2/` - Kind bind-mount example 2
- `k8s/kind-config.yaml` - Kind cluster config

## Prerequisites

- Docker knowledge (required)
- kubectl installed and configured
- A local Kubernetes cluster (kind, minikube, or Docker Desktop)

## Getting started

1. Clone the repo
2. Choose an example under `k8s/`
3. Apply the manifests using `kubectl apply -f`

## Roadmap

- Add Terraform modules and workflows
- Expand Kubernetes examples (deployments, services, ingress)
- Add Docker build and image basics

## Contributing

Open a PR with clear examples and short notes on the why.
