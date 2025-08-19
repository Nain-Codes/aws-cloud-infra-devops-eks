# AWS Cloud Infrastructure with Terraform & EKS

Production-grade DevOps project that provisions AWS infrastructure using **Terraform**, deploys to **Amazon EKS (Kubernetes)**, and enables **CI/CD with GitHub Actions**.

## Highlights
- Infrastructure as Code (Terraform) with modular layout
- Secure VPC, subnets, NAT/IGW, IAM roles & policies
- EKS (managed node groups), Kubernetes manifests (Deployment/Service/Ingress)
- Dockerized sample app
- CI/CD (GitHub Actions) for build, scan, and deploy
- Cost-conscious defaults and tagging strategy

## Repo Map

aws-cloud-infra-devops-eks/
├─ docs/
│ ├─ architecture-diagram.png
│ └─ setup-guide.md
├─ terraform/
│ ├─ provider.tf
│ ├─ main.tf
│ ├─ networking.tf
│ ├─ eks-cluster.tf
│ ├─ iam-roles.tf
│ ├─ variables.tf
│ └─ outputs.tf
├─ k8s-manifests/
│ ├─ app-deployment.yaml
│ ├─ app-service.yaml
│ └─ ingress.yaml
└─ docker/
└─ Dockerfile


## Getting Started
See `docs/setup-guide.md` for step-by-step instructions, screenshots, and commands.
