# kuberNotes
## Notes for CKA Preparation
## This is a test only.
### Certified Kubernetes Administrator (CKA), 2nd Ed O'reilly
#### 1.1 Understanding Kubernetes Core Functions

Kubernetes is all about the container. 

- Kubernetes is all about a container. And this container can be offered by anything. So it doesn't really matter what platform it's coming from. 
- Kubernetes makes sure that the container is available. 
- In order to do so Kubernetes is running a cluster. 
- This cluster typically contains a couple of nodes, which includes a Controller node and the Worker nodes. 
- The Worker nodes is where you are running your container engine. Kubernetes makes sure that the container is running somewhere in this cluster. 
- Cluster can be used in different ways. 
- For now it's just a couple of nodes to make sure that the container is going to be available. In order to do that, Kubernetes works with the Pod. 
- The Pod is a minimal entity that is managed by Kubernetes. 
- The Pod has the IP address. 
- It's a very important part of Kubernetes because Kubernetes doesn't manage containers. 
- Kubernetes manages Pods. 
- In many cases you don't manage the Pods directly as shown. 
- In order to manage Pods, Kubernetes is adding another layer. And this other layer is a layer of the deployment. 
- You could say that your deployment is your application. So if you're going to run an application, basically you are going to run a deployment. 
- Deployments add an important figure. And this figure is replication. And the replication make sure that multiple instances of the same Pod can be running. 
- Apart from that the Kubernetes API defines other objects.
- Kubernetes manages the deployment, make sure that the replicated Pods are offered by all the different Worker nodes. And that brings scalability. And that brings ease of using your application. 
- Also Kubernetes is an important part in a DevOps environment. Because the idea is that developers focus on creating their applications and within the CI/CD pipeline, they make sure that container images are created automatically. And these container images are managed by Kubernetes. And this is all we need to know to get started.



