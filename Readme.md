# Kubernetes RBAC Controller on Minikube Cluster

In this demo, we will see how to use RBAC controller for managing access to your Kubernetes resources.

## Pre-requisites to implement this project:

- Create 1 virtual machine on AWS with 2 CPU, 4GB RAM (t2.medium)
- Setup Minikube on it
- Check Minikube cluster status and nodes:

```bash
minikube status
kubectl get nodes
