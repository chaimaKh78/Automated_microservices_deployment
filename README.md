# Automated Microservices Deployment on Kubernetes

This project presents an automated and modular solution for deploying a microservices-based application architecture to a Kubernetes cluster. It follows modern DevOps and GitOps practices and is structured to support multiple environments (dev/prod) using Helm and Kustomize.

---

## 🌐 Project Description

The application is composed of several microservices, each deployed independently:

- A front-end service developed with Angular
- Two back-end services developed with Spring Boot
- A Eureka service for service discovery
- A gateway for routing traffic between services
- A relational database for persistence

All components are containerized and managed via Helm charts, with environment-specific configurations handled through Kustomize overlays.

---

## ✅ Key Advantages

- **Modular Architecture**: Each microservice is isolated, versioned, and independently deployable.
- **Environment Separation**: Clear distinction between dev and prod configurations through overlays.
- **GitOps Ready**: Compatible with GitOps tools like FluxCD or ArgoCD for automatic deployments from Git.
- **Scalability**: Designed to scale horizontally across services depending on workload.
- **Maintainability**: Code and configuration are organized for clarity and reusability.
- **Consistency**: All deployments are defined declaratively to avoid configuration drift.

---

## 🧱 Use Case

This project is ideal for:

- Demonstrating GitOps deployment workflows with real microservices
- Practicing Kubernetes-native application delivery
- Preparing for DevOps roles requiring AKS, Helm, and microservice architecture
- Deploying an application in a scalable and reproducible manner

