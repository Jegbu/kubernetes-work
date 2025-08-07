# Kubernetes Work

This repository documents my journey as I master Kubernetes hands-on through labs, YAML configurations, and eventually a full-scale project.

## 📘 Courses Followed

- ✅ Kubernetes for Beginners (KodeKloud)
- ⏳ CKA Certification Path (KodeKloud – in progress)

## 🧠 Concepts Covered
- [x] Containers
- [x] Container Orchestration
- [x] Kubernetes Architecture
- [x] Pods and YAML manifests
- [x] ReplicaSets and scaling
- [x] Label selectors and matching
- [x] Deployments and Rollbacks
- [x] Networking Basics
- [x] Services and Networking
- [x] Microservices Architecture
- [ ] Volumes and Persistent Storage
- [ ] Namespaces
- [ ] Multi-node setup with kubeadm

## 📁 Folder Structure

- `pods/` — Basic pod definitions
- `replicasets/` — ReplicaSet and scaling logic
- `deployments/` — Deployments, rollbacks and upgrades
- `services/` — Networking, types of services like node port, clusterIP, and LoadBalancers and how to configure them
    - ![alt text](image.png) Default nginx webpage with ports configured
- `voting-app-demo/` — Microservices architecture showcasing the use of services and how it connects to other pods in. a microservices architecture
    - ![alt text](image-1.png) Voting App microservice
    - ![alt text](image-2.png) Result services which confirms access to the node ports and the services are communicating to one another
## 🚀 Next Steps

- Continue with KodeKloud CKA Labs
- Launch full local cluster for offline LLM + Wikipedia project
- Share journey on LinkedIn + Dev.to
