

🚀 Build a Kubernetes Cluster Locally with Minikube

🎯 Objective

I created this project to deploy and manage applications in Kubernetes using Minikube, kubectl, and Docker. The goal was to get hands-on experience with Kubernetes basics, including deployments, services, scaling, and debugging.


---

🛠 Tools & Technologies I Used

Minikube – To set up a local Kubernetes cluster

kubectl – For managing Kubernetes resources

Docker – To work with containerized applications

YAML – For Kubernetes configuration files



---

🏗 Kubernetes Architecture 

Kubernetes is a container orchestration platform that follows a master-worker architecture.

Master Node (Control Plane) – Manages the cluster and handles scheduling, scaling, and resource allocation.

API Server – Frontend for the cluster.

Scheduler – Assigns workloads to worker nodes.

Controller Manager – Monitors and maintains the desired state.

etcd – Key-value store for cluster data.


Worker Nodes – Run application workloads.

Kubelet – Communicates with the control plane and manages containers.

Kube Proxy – Handles networking.

Container Runtime – Runs the containers (e.g., Docker).




---

📋 How I Built This Project

1️⃣ Installed & Started Minikube

I installed Minikube on my system and started the Kubernetes cluster.

2️⃣ Verified the Cluster

I used kubectl cluster-info and kubectl get nodes to make sure the cluster was running.

3️⃣ Created a Deployment

I wrote a deployment.yaml file for my application, defined the image, replicas, and ports, and applied it using kubectl apply.

4️⃣ Exposed the App with a Service

I created a service.yaml file to expose my app and make it accessible, then applied it with kubectl apply.

5️⃣ Checked Pods & Services

I ran commands like kubectl get pods and kubectl get services to verify everything was running as expected.

6️⃣ Scaled the Deployment

I scaled my app using kubectl scale to test Kubernetes scaling features.

7️⃣ Inspected & Debugged Resources

I used kubectl describe and kubectl logs to check details and troubleshoot issues.

8️⃣ Accessed the Application

I opened the app in my browser using minikube service.


---

📦 Outcome

By building this project myself:

✅ Learned Kubernetes fundamentals (Deployment, Service, Scaling) 

✅ Practiced using Minikube for local Kubernetes setup

✅ Gained confidence in using kubectl commands for real-world projects


