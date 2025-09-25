**Note:** This project is a fork of `opentelemetry-demo`. Thanks to the team and contributors for opensourcing this wonderful demo project. Definitely one of the best on internet.

<!-- markdownlint-disable-next-line -->

## Welcome to the OpenTelemetry Astronomy Shop Demo

## Overview

This project demonstrates CI/CD automation, Kubernetes deployment, and observability for microservices-based applications using OpenTelemetry, GitOps (ArgoCD), Docker, and AWS EKS. The goal is to simulate a real-world DevOps workflow and provide hands-on experience with modern cloud-native practices.

Features

CI/CD Automation: Pipelines created using GitHub Actions for microservices (Java, Python, Golang).

GitOps Deployment: Continuous deployment of services using ArgoCD to Amazon EKS.

Kubernetes Infrastructure: Cluster provisioning and management via Terraform with remote backend on S3 + DynamoDB locking.

Observability: Monitoring and tracing using OpenTelemetry, Prometheus, and Grafana.

AWS Networking: Configured VPC, Load Balancers (ALB), Ingress, Route53, and IAM for secure and scalable deployments.

Custom Domain Access: Sample deployment accessible via a placeholder domain (example.com).


## Tech Stack

Cloud Platforms: AWS (EKS, EC2, S3, VPC, Route53)

Containerization: Docker

Orchestration: Kubernetes (EKS, Minikube), Ingress, ALB

CI/CD & GitOps: GitHub Actions, ArgoCD

Infrastructure as Code: Terraform

Monitoring & Observability: OpenTelemetry, Prometheus, Grafana

Programming Languages: Java, Python, Golang

## Key Learnings

Hands-on experience with GitOps workflows using ArgoCD.

Deployment of multi-language microservices on AWS EKS.

Managing Kubernetes infrastructure as code with Terraform and secure remote state.

Implementing observability using OpenTelemetry, Prometheus, and Grafana.

Understanding AWS networking components and configuring secure access to services.
