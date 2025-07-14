# 🚀 GitOps CI/CD with ArgoCD, Kubernetes & GitHub

As a **Cloud and DevOps enthusiast**, I built a hands-on project implementing a **declarative GitOps-based CI/CD pipeline** using **ArgoCD**, **Kubernetes**, and **GitHub**.

This project automates deployment workflows and maintains state consistency across Kubernetes environments using GitOps principles.

## 🎯 Project Objective

Deploy a web application to a Kubernetes cluster with **ArgoCD** managing the application state declaratively and automatically from a **GitHub** repository. The process is:

- Automated  
- Secure  
- Observable  

## 🧭 Project Architecture

GitHub Repo (App Manifests) - > ArgoCD (in K8s) - > Kubernetes Cluster (App Deployed via Sync)

## 🛠️ Tools & Technologies
Kubernetes (minikube or kubeadm)

ArgoCD (GitOps CD tool)

Kustomize (for overlays)

YAML, Git CLI, ArgoCD CLI

GitHub (source of truth for manifests)

NodePort (for ArgoCD Dashboard exposure)




