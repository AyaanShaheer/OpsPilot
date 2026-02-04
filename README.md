# OpsPilot - AI-Powered Developer Operations Platform

Cloud-native AI platform for intelligent developer workflows.

## Architecture

![High Level Architecture](D:\Download_Folder_D\Gemini_Generated_Image_q9kcmwq9kcmwq9kc.png)


- **Frontend**: Next.js + TailwindCSS + shadcn/ui
- **API**: FastAPI + LangGraph
- **Services**: Go microservices
- **Infrastructure**: AWS EKS, RDS, Redis, Qdrant
- **CI/CD**: GitHub Actions + ArgoCD

## Project Structure
```
ops-pilot/
├── services/          # Microservices
├── k8s/              # Kubernetes manifests
├── infra/terraform/  # Infrastructure as Code
├── .github/          # CI/CD workflows
└── docs/             # Documentation
```

## Development Environment
- **Windows**: Coding, Git, Terraform
- **CentOS VM**: Docker, k3s, K8s testing
- **AWS**: Production deployment
