# DevOps Learning Path

A practical, incremental learning path for DevOps fundamentals.
Start with Kubernetes basics, move into Terraform, and round out with Docker fundamentals.

## Path overview

1. Kubernetes basics (current)
   - Namespace: Divide cluster resources between multiple users. ([Docs](https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/))
   - Pod: The smallest deployable unit, running one or more containers. ([Docs](https://kubernetes.io/docs/concepts/workloads/pods/))
   - ReplicaSet: Keep a stable number of pod replicas running. ([Docs](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/))
   - Deployment: Manage stateless apps with rolling updates and rollbacks. ([Docs](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/))
   - Service: Expose a set of pods with a stable networking endpoint. ([Docs](https://kubernetes.io/docs/concepts/services-networking/service/))
   - Job: Run pods to completion. ([Docs](https://kubernetes.io/docs/concepts/workloads/controllers/job/))
   - CronJob: Schedule jobs at specific times or intervals. ([Docs](https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/))
   - DaemonSet: Ensure a pod runs on all or selected nodes. ([Docs](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/))
   - StatefulSet: Manage stateful apps with stable identities and storage. ([Docs](https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/))
   - ConfigMap: Store non-sensitive configuration data. ([Docs](https://kubernetes.io/docs/concepts/configuration/configmap/))
   - Secret: Store sensitive configuration data. ([Docs](https://kubernetes.io/docs/concepts/configuration/secret/))
   - Ingress: Manage external HTTP(S) access to services. ([Docs](https://kubernetes.io/docs/concepts/services-networking/ingress/))
   - Gateway API: Advanced, role-oriented traffic routing. ([Docs](https://kubernetes.io/docs/concepts/services-networking/gateway/))
   - PersistentVolume and PersistentVolumeClaim: Provision and claim persistent storage. ([Docs](https://kubernetes.io/docs/concepts/storage/persistent-volumes/))
   - RBAC (Role-Based Access Control): Manage permissions and access. ([Docs](https://kubernetes.io/docs/reference/access-authn-authz/rbac/))
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
