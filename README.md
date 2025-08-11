Build a Kubernetes Cluster Locally with Minikube

Objective
This task was focused on learning to deploy and manage applications within a local Kubernetes environment using Minikube, 
kubectl, and Docker.

Tools Used

Minikube: A tool that runs a single-node Kubernetes cluster locally.


kubectl: The command-line tool for interacting with a Kubernetes cluster.


Docker: Used to build and manage container images.

Steps Taken

Minikube Cluster Setup: I installed Minikube and started a local Kubernetes cluster using the minikube start command.


Application Deployment: I created a deployment.yaml file to define my application, specifying the Docker image to be used and the desired number of replicas.


Service Exposure: I wrote a service.yaml file to expose the application so it could be accessed from outside the cluster.


Verification: I used kubectl get pods to verify that the pods were running as expected. I also used 

kubectl get services to check the service status.


Scaling: I practiced scaling the application by using the kubectl scale command to adjust the number of running pods.


Troubleshooting: I used kubectl describe to inspect the details of the pods and services, which helped with understanding their state and any potential issues.

Deliverables

deployment.yaml: The YAML file for the application deployment.


service.yaml: The YAML file for exposing the service.


screenshots/: A directory containing screenshots that show the pods and services running successfully.
