# CKAD Exam Prep ☸️

Welcome to the **CKAD Exam Prep** repository! This repository contains a collection of resources, manifests, and practical exercises designed to help you prepare for the **Certified Kubernetes Application Developer (CKAD)** exam. 

## 📁 Repository Structure

The repository is organized progressively into different sections, covering key concepts tested in the CKAD exam:

* 📂 **`1.KubenetesBasics`** Contains fundamental Kubernetes concepts and objects. This includes basic pods, replica sets, deployments, and services to get you comfortable with core Kubernetes primitives.

* 📂 **`2.DeployingStatefulAppInCluster`** Focuses on deploying and managing stateful applications within a Kubernetes cluster. Includes manifests and exercises on Persistent Volumes (PVs), Persistent Volume Claims (PVCs), and StatefulSets.

* 📂 **`3.HELM/helm-sample`** Covers Helm, the package manager for Kubernetes. Contains sample Helm charts and exercises to practice creating, packaging, deploying, and managing applications via Helm (a critical topic in the updated CKAD curriculum).

* 📂 **`4.Advanced/1 - RollingBackStrategies`** Explores advanced deployment concepts, specifically focusing on rolling updates and rollback strategies to ensure zero-downtime deployments and safe application lifecycle management.

## 🚀 Prerequisites

To make the most out of these exercises, you will need the following tools set up on your local machine:
* A working Kubernetes cluster (e.g., [Minikube](https://minikube.sigs.k8s.io/docs/start/), [kind](https://kind.sigs.k8s.io/), or Docker Desktop).
* [`kubectl`](https://kubernetes.io/docs/tasks/tools/) command-line tool installed and configured to interact with your cluster.
* [`helm`](https://helm.sh/docs/intro/install/) installed for the Helm-specific exercises.
