

# MongoDB Deployment on Kubernetes with Minikube

Within this repository, I've curated a comprehensive guide to deploy MongoDB on Kubernetes, leveraging essential components like Pods, internal and external Services, and harnessing the power of Minikube. The objective here is to facilitate a seamless learning experience in deploying applications within a Kubernetes environment. You'll find a collection of YAML files for MongoDB, each tailored to specific configurations, ensuring a smooth deployment process. Additionally, I've included a detailed set of commands for both Minikube and kubectl, laying the foundation for a successful deployment. This repository serves as a hands-on resource, providing users with a structured, step-by-step approach to mastering the deployment of applications on Kubernetes using Minikube. Explore the files and instructions provided to gain a practical understanding of this dynamic deployment process. Happy learning!



## Prerequisites

Ensure You Have kubectl and Minikube Installed





## Installation

If you're using a Mac, you can easily set up Minikube and kubectl with the following straightforward commands.

1. Install the minikube using command:
```bash
  brew install minikube
```
    
2. Start the minikube :
```bash
  minikube start --driver=docker
```

3. Install kubectl :
```bash
  brew install kubectl 
```
## Commads for Kubectl

#### Make clone of this repository to your system. 

1. Make the pod from the mongo.yaml file
```bash
 kubectl apply -f mongo.yaml
```

2. Again make the pod of mongo-express.yaml
```bash
 Kubectl apply -f mongo-express.yaml
```
3. Now just do same with Secret.yaml file
```bash
 Kubectl apply -f Secret.yaml
```
4. Now make ConfigMap of the configMap.yaml file
```bash
 Kubectl apply -f configMap.yaml
```
5. List the pods
```bash
  kubectl get pods
```
6. List secrets
```bash
  kubectl get secret
```

## Commands of minikube

This MongoDB deployment utilizes Minikube commands for easy local Kubernetes cluster management. It features two key services: an External Service to handle incoming requests, and an Internal Service for internal MongoDB pod communication. Together, they ensure smooth MongoDB interactions, highlighting Kubernetes' effectiveness in microservices orchestration.

1. Before use minikube fire this command to list the services.
```bash
 kubectl get services
```
2. Then minikube the pending/external service shown in the list
```bash
 minikube service mongo-express-service
```

 

## Screenshots

<img width="1690" alt="Screenshot 2023-11-09 at 2 51 22 PM" src="https://github.com/RaviChandra001/mongodb-App/assets/134200599/44865c3b-2a5e-4559-b2ce-22521af86aa5">

## Features 

- Orchestration
- Containerization 
- Scaling
- Load Balancing


## About Me

💡 Currently learning DevOps

🤝 Looking for help to work on DevOps projects

💬 Ask me about anything related to DevOps

📫 Connect with me on LinkedIn

⚡️ Fun fact: DevOps is too easy!

## Support

For support, email raviamazon1101@gmail.com or contact me on Linkedin.


## 🔗 Links
[![GitHub](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/RaviChandra001)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)


![Uploading Kubernetes-Logo.jpg…]()


