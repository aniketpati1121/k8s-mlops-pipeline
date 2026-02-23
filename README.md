# k8s-mlops-pipeline

An end-to-end **production-level MLOps pipeline implementation on Kubernetes**.

This repository demonstrates how to build, deploy, and manage Machine Learning workflows using **Kubeflow Pipelines (KFP)** in a Kubernetes environment.

---

## Overview

This project showcases:

- Containerized ML workloads
- Pipeline orchestration using Kubeflow Pipelines
- Kubernetes-native deployment
- Production-style project structure
- Reproducible ML workflows

---

## Project Structure

k8s-mlops-pipeline/
│
├── LICENSE
├── README.md
├── hello_pipeline.py
├── iris_pipeline.py
├── hello_world_pipeline.yaml
├── iris_pipeline.yaml


---

## Included Pipelines

### Iris Pipeline

A classic Machine Learning workflow using the **Iris dataset**.

**Details:**
- Dataset: Iris Dataset
- Algorithm: Random Forest
- Steps:
  - Data loading
  - Model training
  - Model evaluation
  - Pipeline compilation

This pipeline demonstrates a realistic ML workflow deployed on Kubernetes.

---

### Hello Pipeline

A minimal example pipeline used for:

- Verifying Kubeflow installation
- Testing pipeline compilation
- Understanding basic pipeline structure
- Quick experimentation

Perfect for beginners and debugging.

---

## Tech Stack

- Kubernetes
- Kubeflow Pipelines (KFP v2)
- Docker
- Python
- scikit-learn

---

## 🐳 Setup & Usage

### 1️⃣ Clone Repository

```bash
git clone https://github.com/<your-username>/k8s-mlops-pipeline.git
cd k8s-mlops-pipeline