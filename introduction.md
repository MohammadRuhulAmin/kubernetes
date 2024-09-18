## Kubernetes

### What is kubernetes ?
- It is an open source container orchestration tool
- Developed By Google
- Helps to manage containerized applications in different deployment environments
- possible to deploy on physical, virtual, hybrid etc

### What problems does Kubernetes Solve?
- High Availability or no downtime
- Scalability or high performance
- disaster recovery - backup and restore

### Kubernetes Components:
- Pod
- Service
- Ingress
- Volumes
- Secrets
- ConfigMap
- StatefulSet
- Deployment

### What is Node / Worker Node in Kubernetes ?
- In kubernetes, a node (also known as worker node) is a physical or virtual machine that runs the applications and services managed by the kubernetes control plane. Each node in kubernetes cluster is responsible for running the pods that contain your application workloads.

### What is Pod?
- the smallest unit of K8s and it is an abstruction over container 
- it creates the running environment 
- usually 1 application per Pod
- each pods has its own ip address.
- in kubernetes, a Pod is the smallest and simplest unit in the Kubernetes object model. It represents a single instance of a running process in  your cluster. A Pod can run one or more containers, usually Docker containers. These containers are tightly coupled and share the same network namespace and storage volumes.
- Pods can specify volumes that containers can use to persist data, and they share the same IP address and port space, allowing communication between containers easily. 
- Pods are designed to be ephemeral. If a Pod dies, Kubernetes replaces it automatically by creating a new instance, however the new Pod will have a different IP address and identity.

### What is Service and ingress in Kubernetes ?
- It has a permanent IP address. Lifecycle of Pod and Service Not connected means if a Pod dies, the service will remain same or unchange.
- In Kubernetes, Ingress is an API object that manages external access to services within a cluster, typically HTTP and HTTPS. It acts as a smart routing system, allowing you to expose your Kubernetes services to the outside world and define rules for how requests should be routed to different services
 
