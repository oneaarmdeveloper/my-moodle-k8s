# Moodle on Kubernetes

This repo contains my Helm values and config to deploy Moodle on Minikube.

## How to Use
1. Install Minikube and Docker.
2. Run `helm install my-moodle bitnami/moodle --version 27.0.5 --namespace ichek-moodle -f helm/values.yaml`
