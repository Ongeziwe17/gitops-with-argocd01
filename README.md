# GitOps with ArgoCD: NGINX on Minikube

This is a small learning project to explore GitOps practices using [ArgoCD](https://argo-cd.readthedocs.io/en/stable/) for continuous deployment to a local Kubernetes cluster managed by [Minikube](https://minikube.sigs.k8s.io/docs/). The application deployed is a simple NGINX web server.

## 🚀 Tools Used

- **Minikube**: Local Kubernetes cluster for development/testing
- **kubectl**: CLI tool to interact with the Kubernetes cluster
- **ArgoCD**: GitOps continuous delivery tool for Kubernetes
- **NGINX**: Lightweight web server used as the sample application

## 📂 Project Structure

```text
.
├── deployment.yaml   # Kubernetes Deployment for NGINX: Defines a Deployment that runs **2 replicas** of the NGINX container with basic resource limits
└── service.yaml      # Kubernetes Service to expose NGINX via NodePort

