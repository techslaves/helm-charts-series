## What is helm?

**Helm is  basically a package manager for Kubernetes. Like we have ‘Yum’ or ‘Apt’ for Linux
But instead of installing system packages, Helm helps you install applications into Kubernetes clusters.**

**A Helm chart is simply a bundle of YAML templates — Deployment, Service, ConfigMap, Ingress, everything — all packaged neatly with configuration.**

## **Why Do We Use Helm?**

**“If you’ve deployed anything non-trivial on Kubernetes, you know the pain — dozens of YAML files, copy-paste errors, version mismatches, and complexity.”**

**“Helm solves all this by giving us:”**

- **Reusable templates instead of static YAML**
- **One command to install complete applications (**`helm install argocd argo/argo-cd --namespace argocd`**)**
- **Versioning and rollback support**
- **Easily configurable deployments**
- **A huge library of community and vendor charts**

## **Helm Concepts – Chart, Release, Repository**

**“There are three basic concepts in Helm:”**

### **1. Chart**

“A chart is the package — a templated set of Kubernetes manifests.”

### **2. Release**

“When you install a chart, Helm creates a *release* — a running instance of that chart.”

### **3. Repository**

“A repo is where charts are stored — like Docker Hub for docker image.”
