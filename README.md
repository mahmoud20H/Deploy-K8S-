Kubernetes Cluster Setup using Kubeadm
This repository contains the steps and configuration files to install a Kubernetes cluster using kubeadm on multiple nodes.

Table of Contents
Introduction
Requirements
Cluster Architecture
Installation Steps
Post-Installation
Common Issues
Contributing
License
Introduction
Kubernetes is an open-source platform designed to automate the deployment, scaling, and operation of application containers. This repository focuses on setting up a Kubernetes cluster using kubeadm, a simple way to bootstrap a Kubernetes cluster.

Requirements
System Requirements
Operating System: Ubuntu 20.04 (or any other Linux distribution)
Memory: At least 2 GB RAM per node
CPU: At least 2 CPUs per node
Storage: Minimum 10 GB free disk space per node
Network: Stable network connectivity
Software Requirements
Docker (or any container runtime compatible with Kubernetes)
kubeadm, kubectl, kubelet installed on all nodes
SSH access to all nodes
Firewall rules to allow inter-node communication on the required ports
Cluster Architecture
This setup involves:

Master Node: Controls the cluster, schedules workloads, and manages resources.
Worker Nodes: Hosts the application workloads.
