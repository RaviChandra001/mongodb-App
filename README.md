
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

![App Screenshot](https://jksdjhksdkhj.s3.ap-south-1.amazonaws.com/Screenshot%202023-11-09%20at%202.51.22%20PM.png?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCmFwLXNvdXRoLTEiSDBGAiEAlhj4FZNpKOI5XUugOtaUe2h0UTAOjDvRulLmoJ2OZ1gCIQChiIaOioaFkWPVDugI6LQM0sRWzp06I1RkUvZ%2Bt5FWmSrtAgjS%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDIzMDQyMDk3OTE3MCIMmmmmnhC9A6hwNfkmKsEC13IuI2944eiYUHdCkRm9ggiYymyd1pydqgU%2B4UNwTYWliNUAucwkX4ad3N%2FBjq55UPg7keqMZVR8CG%2FnkSQYAEcLgflVu27s1Gu2KJZQuDCPFyelKbQNb53wwFXnADgtFUc9ryEruDOkuKnP4CGyGgR2ly%2FwLfhqyo8adtCp21xTc9F%2B70m8VUS2Ultbx2LitgkOWJ9pOgJnD7yzezuO4ddHnL8ImLelgk6QiMiLumfd6lrRPwNtfnS42scRLclb5jAnKQeOQ0kZ5h7WcgXn2zXjvu8K5yGOyn4Ui1JJP12sso02gQAVeQWwRKRCPVJpUzdZiVoxV%2Fek2MDu6Scv%2F4KxskOTxEchGAVXDkr7hjRb3EfWLwgP5ZNYuY4HdLb4V5W7Jz8GwQfTHMJ%2BXV40NS7HJKGYDrwA3D%2BQFKoKDCBfMMfGsqoGOrICdUupPmmze8J7y3Fpk0MO1ed%2FWgk45i587CDI1supwEOXB65vv0nmt8TzX8cqI1G8OXMmb5PkuagU6U9uY3R5Xc0KLTMH3MV%2BCidSW4KgExBJRzZz8TTG4rbJZY2oz%2B%2FiwhoV%2FEEd1X3JlAg9%2F4X3nT8AodJXQeUKWEHRap6Ea75b2f3MxqeCLeDt%2BF1sFZDUnlKbMYYko1SEPkwm6uvlFeIjORG%2FmkJsWGsJM3IfX8A5j1kXAWQLwS6SlPXG2q%2Be7LRgViI60%2BdLZ5zADzOw%2BibIPwXfA4F%2B9djmYIiGCMx7qMF%2FUSIh2ilad4Gd7ZIInfftA5YwObKOuOz1G5GEnrCbn2VTUEG%2FEGGDXC979LoNUpetfi1CKGhlTEs32V6%2Bcn2TpX%2BKNLZbo337DJ7B71rA&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231109T092216Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIATLJRJDXRBYT4VH4Y%2F20231109%2Fap-south-1%2Fs3%2Faws4_request&X-Amz-Signature=8078b75d64cba2999b18d5f5238082caebf219bc5742a06cbe57a5b9b990ae43)


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



![Logo](https://jksdjhksdkhj.s3.ap-south-1.amazonaws.com/Kubernetes-Logo.jpg?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJn%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCmFwLXNvdXRoLTEiSDBGAiEAlhj4FZNpKOI5XUugOtaUe2h0UTAOjDvRulLmoJ2OZ1gCIQChiIaOioaFkWPVDugI6LQM0sRWzp06I1RkUvZ%2Bt5FWmSrtAgjS%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDIzMDQyMDk3OTE3MCIMmmmmnhC9A6hwNfkmKsEC13IuI2944eiYUHdCkRm9ggiYymyd1pydqgU%2B4UNwTYWliNUAucwkX4ad3N%2FBjq55UPg7keqMZVR8CG%2FnkSQYAEcLgflVu27s1Gu2KJZQuDCPFyelKbQNb53wwFXnADgtFUc9ryEruDOkuKnP4CGyGgR2ly%2FwLfhqyo8adtCp21xTc9F%2B70m8VUS2Ultbx2LitgkOWJ9pOgJnD7yzezuO4ddHnL8ImLelgk6QiMiLumfd6lrRPwNtfnS42scRLclb5jAnKQeOQ0kZ5h7WcgXn2zXjvu8K5yGOyn4Ui1JJP12sso02gQAVeQWwRKRCPVJpUzdZiVoxV%2Fek2MDu6Scv%2F4KxskOTxEchGAVXDkr7hjRb3EfWLwgP5ZNYuY4HdLb4V5W7Jz8GwQfTHMJ%2BXV40NS7HJKGYDrwA3D%2BQFKoKDCBfMMfGsqoGOrICdUupPmmze8J7y3Fpk0MO1ed%2FWgk45i587CDI1supwEOXB65vv0nmt8TzX8cqI1G8OXMmb5PkuagU6U9uY3R5Xc0KLTMH3MV%2BCidSW4KgExBJRzZz8TTG4rbJZY2oz%2B%2FiwhoV%2FEEd1X3JlAg9%2F4X3nT8AodJXQeUKWEHRap6Ea75b2f3MxqeCLeDt%2BF1sFZDUnlKbMYYko1SEPkwm6uvlFeIjORG%2FmkJsWGsJM3IfX8A5j1kXAWQLwS6SlPXG2q%2Be7LRgViI60%2BdLZ5zADzOw%2BibIPwXfA4F%2B9djmYIiGCMx7qMF%2FUSIh2ilad4Gd7ZIInfftA5YwObKOuOz1G5GEnrCbn2VTUEG%2FEGGDXC979LoNUpetfi1CKGhlTEs32V6%2Bcn2TpX%2BKNLZbo337DJ7B71rA&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231109T092006Z&X-Amz-SignedHeaders=host&X-Amz-Expires=299&X-Amz-Credential=ASIATLJRJDXRBYT4VH4Y%2F20231109%2Fap-south-1%2Fs3%2Faws4_request&X-Amz-Signature=c8814ad5dd0000dc4f6d83e0619c7fe7636dd6fd12cf6408992d212f76bd0474)

