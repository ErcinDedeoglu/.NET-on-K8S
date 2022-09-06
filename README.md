# .NET on K8S

This repo is a demo project to demonstrate techniques for building .NET services for Kubernetes. The purpose of this repo is to show how .NET developers can use kubernetes and .NET in conjunction, to build production-quality applications.

Using with Docker Desktop with Kubernetes installed:

1. Build

`docker build -t merhaba-service:0.0.1 .`

2. Deploy

`kubectl apply -f merhaba-service-deployment.yaml`