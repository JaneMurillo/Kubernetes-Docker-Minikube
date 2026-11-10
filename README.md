# Kubernetes: Ingress, LoadBalancer & Rancher

## Overview

This project explores Kubernetes networking and cluster management through the implementation and configuration of Ingress, LoadBalancer, and Rancher.

The main objective is to understand how applications running inside a Kubernetes cluster can be exposed and accessed externally, as well as how cluster resources and deployments can be managed through different tools.

The project covers practical concepts related to container orchestration, service networking, traffic routing, and Kubernetes infrastructure management.

## Project Objectives

- Understand Kubernetes service exposure mechanisms.
- Explore the differences between ClusterIP, NodePort, and LoadBalancer services.
- Understand how Ingress manages external HTTP and HTTPS traffic.
- Explore traffic routing between external requests and Kubernetes services.
- Learn how Rancher simplifies Kubernetes cluster management.
- Understand the fundamentals of container orchestration and cluster administration.

## Technologies Used

- **Kubernetes:** Container orchestration platform for deploying and managing applications.
- **Docker:** Containerization technology for packaging and running applications.
- **Minikube:** Tool for running local Kubernetes clusters.
- **Ingress:** Kubernetes resource for managing external HTTP and HTTPS access to services.
- **LoadBalancer:** Kubernetes service type for exposing applications through external load balancing.
- **Rancher:** Platform for managing and monitoring Kubernetes clusters.

## Key Concepts

### Kubernetes Ingress

Ingress provides a mechanism for managing external HTTP and HTTPS access to services running inside a Kubernetes cluster.

It enables traffic routing based on hostnames and URL paths, allowing multiple applications to be accessed through a common entry point.

### LoadBalancer

The LoadBalancer service type exposes Kubernetes applications externally through a load balancing mechanism, distributing incoming traffic to application instances.

### Rancher

Rancher provides a centralized platform for managing Kubernetes clusters, deployments, and infrastructure resources through a graphical interface.

## Learning Outcomes

Through this project, I explored Kubernetes networking concepts and different approaches to exposing applications outside a cluster.

The implementation helped me understand how Ingress and LoadBalancer facilitate external access to containerized applications and how Rancher simplifies Kubernetes infrastructure management.

This experience strengthened my understanding of container orchestration, application networking, and cloud-native infrastructure.

## Technologies & Documentation

- **Kubernetes:** https://kubernetes.io/docs/
- **Docker:** https://docs.docker.com/
- **Minikube:** https://minikube.sigs.k8s.io/docs/
- **Ingress:** https://kubernetes.io/docs/concepts/services-networking/ingress/
- **Rancher:** https://ranchermanager.docs.rancher.com/
