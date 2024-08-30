## kubernetes

Kubernetes is an open-source container orchestration platform that automates the deployment, scaling and management of containerised applications. It allows the efficient management of clusters of containers, handling tasks such as scaling based on resource needs, automated rollouts and rollbacks of update and self healing of containers.
##  Why do we use Kubernetes ?
            
### Scalability:- 
it allows applications to automatically adjust resources to maintain performance without manual intervention.
### Fault Tolerance:- 
Kubernetes enhances applications reliability through automated health checks,self-healing capabilities that replace failed containers and intelligent distribution of traffic across healthy instances.
### Resource Efficiency:- 
by optimizing resource utilization and workload placement, kubernetes helps in achieving cost savings and maximizing hardware utilization.
### Container Orchestration:-
Kubernetes automates the management of containers, simplifying the deployment, scaling and operational tasks associated with containerized applications.
### Portability:- 
Kubernetes provides a consistent platform across various environments enabling applications to run identically on-premises, in the cloud, or across hybrid and multi-cloud setups.
## Components of Kubernetes 
### API server:
All operations such as scheduling and scaling pass through this component. It Acts as the front-end, serving the Kubernetes API.
### Scheduler
Assigns workloads (in the form of pods) to worker nodes based on resource availability and other factors.
### Controller manager 
The Controller Manager in Kubernetes is like a supervisor who watches over different parts of the system to make sure everything is working as expected. If something goes wrong, the Controller Manager takes action to fix it and bring things back to normal.
### Kubelet
The agent that ensures containers are running in pods on a node. It interacts with the API Server to receive tasks and ensures pod states are as expected.
### Pods
A Pod in Kubernetes is the smallest, most basic deployable unit, consisting of one or more containers that share the same network namespace and storage. Pods are the building blocks of a Kubernetes application, managing containerized workloads and services. They encapsulate the container(s) and provide a way to run applications in an isolated environment.
### Deployment 
A Deployment in Kubernetes is a resource object that defines and manages the deployment of a set of identical Pods. It provides declarative updates, ensuring that the desired number of Pods are running, and handles rolling updates, scaling, and rollback of applications without downtime.
### Service 
A Service in Kubernetes is an abstraction that defines a logical set of Pods and a policy for accessing them. It provides a stable IP address and DNS name, allowing for load balancing and reliable communication between different parts of an application, regardless of the actual Pod IPs.
### Container Runtime
Responsible for pulling container images and running containers in pods.

## What is kubectl ?
kubectl is the command-line interface (CLI) tool used to interact with Kubernetes clusters. It allows users to perform various operations on Kubernetes resources, such as pods, services,deployments, and more. kubectl communicates with the Kubernetes API server to execute commands and manage cluster resources. Users can create, inspect, update, and delete.Kubernetes objects using kubectl, as well as perform tasks like scaling deployments, viewing cluster logs, executing commands inside containers,
port-forwarding, and managing configurations. It is a versatile tool that plays a crucial role in managing and operating.Kubernetes clusters efficiently from the command line.


