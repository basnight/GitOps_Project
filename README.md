# GitOps and ArgoCD Complete Hands-on Project

## In this comprehensive hands-on project, we dive deep into the world of GitOps and ArgoCD, demonstrating how to implement these essential DevOps practices step by step.

🐳 Dockerizing the Todo Application: We begin by containerizing the Todo application, ensuring it's ready to be deployed and managed efficiently.

☁️ Provisioning EKS Kubernetes Cluster with Terraform: Next, we'll guide you through provisioning an EKS (Elastic Kubernetes Service) cluster on AWS using Terraform custom modules. Learn best practices for infrastructure as code.

🔄 Implementing CI with CircleCI: Continuous Integration (CI) is crucial to modern software development. Discover how to set up a robust CI pipeline using CircleCI, automating your code integration process.

🌐 GitOps with ArgoCD: GitOps is a game-changer in managing Kubernetes environments. I will show you how to leverage ArgoCD to automate application deployment and synchronization with your Git repository.

🛠️ Fixing Errors in Real-Time: Throughout this video, we'll encounter common challenges and errors that can occur in real-world scenarios. Watch as we troubleshoot and resolve these issues, providing valuable insights into debugging and problem-solving.

## Architecture
![Architecture Diagram](https://cdn-images-1.medium.com/max/800/1*T5IRoSoiqT8qnYLUprsRUQ.png)

## Topics covered
- End to end DevOps project flow using the architectural diagram 
- How to dockerize an application
- How to provision EKS Kubernetes cluster using Terraform custom modules
- How to implement CI using CircleCI
- What is GitOps, and why do we use GitOps 
- How to implement GitOps using ArgoCD
- Testing the application deployed by ArgoCD on the EKS cluster 

## This project contains Three directories

➡️ [App Code] [link](https://github.com/basnight/GitOps_Project/tree/main/AppCode)

➡️ [Terraform code] [link](https://github.com/basnight/GitOps_Project/tree/main/tf)

➡️ [Manifest] [link](https://github.com/basnight/GitOps_Project/tree/main/kube_manifest)

## 📌Commands used for Argocd Setup

kubectl apply -n argocd -f (https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml)

kubectl port-forward svc/argocd-server 8080:443 -n argocd

kubectl get secret argocd-initial-admin-secret -n argocd -o yaml

## 👨‍💻Reference Blogs:
1)   / deploying-dockerized-app-on-aws-eks-cluste...
2)   / how-to-provision-amazon-eks-cluster-using-...  
3)   / how-to-set-pipeline-using-circleci-update-...  
4)   / install-argocd-on-the-eks-cluster-and-conf... 
