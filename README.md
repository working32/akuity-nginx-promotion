# Nginx-Promo

**Overview**
This repository demonstrates a simple GitOps-based promotion workflow using:
NGINX as the sample application
Argo CD for continuous deployment
Kargo for controlled promotion between environments
Kustomize for environment-specific configuration
The goal is to show how application changes flow safely from dev → prod using declarative infrastructure and automated promotion.

**Setup & Overall Design**
Architecture
One Kubernetes cluster
Two logical environments:
edge-dev
