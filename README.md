# DevOps K8s Platform

A production-like Kubernetes platform designed to demonstrate real-world DevOps and SRE practices such as automated delivery, scalability, observability and infrastructure design decisions.

---

## Overview

DevOps K8s Platform is a personal platform engineering project focused on designing and operating a realistic Kubernetes environment.

The main goal of this repository is not only to deploy an application, but to build and operate a complete platform including networking, scaling, monitoring, delivery pipelines and stateful workloads.

---

## Why this project exists

This project was created to practice and demonstrate:

- Production-like Kubernetes architecture design
- End-to-end CI/CD workflows
- Operational observability and monitoring
- Horizontal scaling based on metrics
- Running and operating stateful services inside the cluster
- Documenting infrastructure and architectural decisions

This repository is intended to reflect real operational responsibilities of a DevOps / Platform Engineer.

---

## High-level architecture

The platform consists of the following main layers:

- Ingress and load balancing layer
- Application layer running as Kubernetes Deployments
- Stateful database layer
- Observability stack
- CI/CD pipeline integrated with the cluster

---

## Technology stack

- Kubernetes
- GitLab CI
- Prometheus
- Grafana
- MySQL
- HAProxy

---

## Key capabilities

- Automated application delivery through CI/CD
- Horizontal Pod Autoscaling for stateless services
- Metrics collection and visualization
- Persistent storage for stateful workloads
- Clear separation between platform and application manifests
- Architecture and infrastructure decisions documented

---

## Repository structure


