# ☁️ aws-devops-engineering-lab

> **A structured, hands-on collection of 20 AWS & DevOps projects** — built to bridge the gap between certification knowledge and real-world cloud engineering practice.

[![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Terraform](https://img.shields.io/badge/IaC-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)](https://www.terraform.io/)
[![Docker](https://img.shields.io/badge/Containers-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Kubernetes](https://img.shields.io/badge/Orchestration-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![GitHub Actions](https://img.shields.io/badge/CI/CD-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE) 

---

## 📌 Introduction

This repository is my personal engineering lab — a curated set of 20 progressively complex AWS and DevOps projects that cover the full spectrum of modern cloud infrastructure. Each project is a standalone, deployable unit with real code, automation scripts, and documentation.

The projects range from deploying a static website on S3 to running multi-region active-active architectures, GitOps workflows with ArgoCD, chaos engineering experiments, and enterprise-grade FinOps cost governance. This isn't a tutorial collection — it's a working portfolio that reflects how cloud infrastructure is actually built and managed in professional engineering teams.

I'm working through all 20 projects as part of a structured mentorship program under the guidance of **[@Mide69](https://github.com/Mide69)** — Olamide Kosile — who designed and assigned this learning path.

---

## 🎯 Purpose

Cloud certifications prove you understand the concepts. This repository proves you can apply them.

The goal of this lab is to:

- Build real, deployable infrastructure — not just read about it
- Develop muscle memory with AWS services, Terraform, Docker, Kubernetes, and CI/CD tools
- Create a portfolio that demonstrates depth and progression to recruiters and engineering teams
- Practice the operational discipline required in real DevOps and Cloud Engineering roles: automation, observability, security, and cost awareness

---

## 🛠️ Technologies Used

| Domain | Tools & Services |
|---|---|
| **Cloud Platform** | AWS (EC2, S3, RDS, Lambda, VPC, IAM, CloudFront, Route 53) |
| **Infrastructure as Code** | Terraform, AWS CloudFormation |
| **Containers & Orchestration** | Docker, Amazon ECS, Amazon ECR, Amazon EKS, Kubernetes, Helm |
| **CI/CD & GitOps** | GitHub Actions, AWS CodeDeploy, ArgoCD |
| **Serverless** | AWS Lambda, API Gateway, SQS, DynamoDB |
| **Observability** | CloudWatch, Prometheus, Grafana, Loki |
| **Security** | AWS GuardDuty, Security Hub, AWS Config, Secrets Manager |
| **Reliability & SRE** | Auto Scaling Groups, AWS FIS, Chaos Mesh |
| **FinOps** | AWS Cost Explorer, AWS Budgets, tagging policies, SCPs |
| **Scripting & Automation** | Bash, Python |

---

## 🗂️ Project Structure

Projects are organized into four difficulty tiers. Each lives in its own directory with a dedicated `README.md`, deployment scripts where applicable, and all supporting code.

```
aws-devops-engineering-lab/
│
├── AWS Project 1  - Static Website S3 CloudFront/
├── AWS Project 2  - Linux Server Setup on EC2/
├── AWS Project 3  - Serverless Contact Form/
├── AWS Project 4  - RDS Database/
├── AWS Project 5  - CI-CD Pipeline/
│
├── AWS Project 6  - Infrastructure as Code/
├── AWS Project 7  - Containerize App/
├── AWS Project 8  - Centralized Logging/
├── AWS Project 9  - Secrets Management/
├── AWS Project 10 - Auto Scaling Web Tier/
├── AWS Project 11 - Event-Driven Data Pipeline/
│
├── AWS Project 12 - Kubernetes EKS/
├── AWS Project 13 - GitOps ArgoCD/
├── AWS Project 14 - Full Observability Stack/
├── AWS Project 15 - Blue-Green Canary Deployments/
├── AWS Project 16 - AWS Security Posture/
│
├── AWS Project 17 - Multi-Region Active-Active/
├── AWS Project 18 - Platform Engineering/
├── AWS Project 19 - Chaos Engineering/
├── AWS Project 20 - FinOps Cost Optimization/
│
└── README.md
```

Each project folder typically contains:

```
AWS Project N - Name/
├── README.md        # Architecture overview, step-by-step guide, cleanup, troubleshooting
├── deploy.sh        # One-command deployment (Projects 1–7)
├── cleanup.sh       # Full resource teardown
└── ...              # App code, Terraform configs, Helm charts, Python scripts, etc.
```

---

## 📚 Project Roadmap

### 🟢 Beginner — Projects 1–5 | Foundation (1–2 weeks)

| # | Project | Key AWS Services | Est. Time |
|---|---|---|---|
| 01 | Static Website on S3 + CloudFront | S3, CloudFront, ACM, Route 53 | 1–2 hrs |
| 02 | Linux Server Setup on EC2 | EC2, VPC, Security Groups, Nginx | 2–3 hrs |
| 03 | Serverless Contact Form | Lambda, API Gateway, SES | 2–3 hrs |
| 04 | RDS Database with Backups | RDS, Multi-AZ, CloudWatch | 2–3 hrs |
| 05 | CI/CD Pipeline | GitHub Actions, OIDC, S3 | 2–3 hrs |

### 🔵 Intermediate — Projects 6–11 | IaC, Containers & Observability (2–3 weeks)

| # | Project | Key AWS Services | Est. Time |
|---|---|---|---|
| 06 | Infrastructure as Code | Terraform, VPC, EC2, RDS modules | 3–4 hrs |
| 07 | Containerized Application | Docker, ECS, ECR, ALB | 3–4 hrs |
| 08 | Centralized Logging | CloudWatch, CloudWatch Agent | 3–4 hrs |
| 09 | Secrets Management | Secrets Manager, Lambda rotation | 3–4 hrs |
| 10 | Auto Scaling Web Tier | ALB, ASG, Launch Templates | 3–4 hrs |
| 11 | Event-Driven Data Pipeline | SQS, Lambda, S3, DynamoDB | 3–4 hrs |

### 🟠 Advanced — Projects 12–16 | Kubernetes, GitOps & Security (3–4 weeks)

| # | Project | Key AWS Services | Est. Time |
|---|---|---|---|
| 12 | Kubernetes on EKS | EKS, Helm, HPA, PDB | 4–6 hrs |
| 13 | GitOps with ArgoCD | ArgoCD, Helm, App-of-Apps pattern | 4–6 hrs |
| 14 | Full Observability Stack | Prometheus, Grafana, Loki | 4–6 hrs |
| 15 | Blue/Green & Canary Deployments | CodeDeploy, ALB, ECS | 4–6 hrs |
| 16 | AWS Security Posture | GuardDuty, Security Hub, Config | 4–6 hrs |

### 🔴 Expert — Projects 17–20 | Architecture, Resilience & Cost (4–6 weeks)

| # | Project | Key AWS Services | Est. Time |
|---|---|---|---|
| 17 | Multi-Region Active-Active | Global Accelerator, DynamoDB Global Tables | 6–8 hrs |
| 18 | Platform Engineering | Backstage, Terraform modules, IDP | 6–8 hrs |
| 19 | Chaos Engineering | AWS FIS, Chaos Mesh, steady-state monitoring | 6–8 hrs |
| 20 | FinOps Cost Optimization | Cost Explorer, Budgets, tagging SCPs | 6–8 hrs |

---

## 🧠 Features & Learning Outcomes

By working through all 20 projects, you will have hands-on experience with:

- **Hosting & Networking** — Global content delivery, custom domains, TLS certificates, VPC design
- **Serverless Architecture** — Event-driven functions, API backends, managed queues and databases
- **Infrastructure as Code** — Reusable Terraform modules, remote state, environment parity
- **Containerization** — Docker image builds, ECS task definitions, ECR image lifecycle
- **Kubernetes** — Cluster management on EKS, Helm chart templating, horizontal pod autoscaling
- **GitOps** — Declarative deployments with ArgoCD, automated sync from Git to cluster
- **Observability** — Metrics, logs, and dashboards across the full application stack
- **Deployment Strategies** — Zero-downtime releases using blue/green and canary patterns
- **Security Engineering** — Threat detection, compliance monitoring, secrets rotation
- **High Availability** — Multi-region failover, global load balancing, replicated data stores
- **Resilience Testing** — Injecting failures with AWS FIS to validate system behavior under stress
- **Cost Governance** — Tagging standards, budget alerts, resource right-sizing at scale

---

## ⚙️ Setup & Installation

### Prerequisites

Before starting, make sure you have the following installed and configured:

- [AWS CLI v2](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) — configured with appropriate IAM credentials
- [Terraform](https://developer.hashicorp.com/terraform/install) (>= 1.5)
- [Docker](https://docs.docker.com/get-docker/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [Helm](https://helm.sh/docs/intro/install/)
- [Git](https://git-scm.com/)
- An AWS account with billing alerts configured

> ⚠️ **Billing notice:** Always run cleanup scripts after finishing a project. Most projects cost under $5 if cleaned up within 24 hours. Set a billing alarm before you start.

### Clone the Repository

```bash
git clone https://github.com/ericgitau-tech/aws-devops-engineering-lab.git
cd aws-devops-engineering-lab
```

### Configure AWS CLI

```bash
aws configure
# Enter your Access Key ID, Secret Access Key, region (e.g. us-east-1), and output format
```

---

## 🚀 Usage

### Automated Projects (1–7)

Projects 1 through 7 include deployment and cleanup scripts. Running them is straightforward:

```bash
cd "AWS Project 2 - Linux Server Setup on EC2"
bash deploy.sh
# Follow the output, test your setup, then tear it down:
bash cleanup.sh
```

### README-Driven Projects (8–20)

Projects 8 through 20 are guided via each project's own `README.md`. All CLI commands are complete and copy-pasteable — open the README and follow each step in sequence.

```bash
cd "AWS Project 14 - Full Observability Stack"
# Open README.md and follow the step-by-step guide
```

### Recommended Approach

- Work through projects in order if you're new to any of these domains
- Read each project's architecture section before deploying — understand what you're building before you build it
- After deployment, deliberately break things and observe what happens; that's where the real learning is
- Always run the cleanup before moving to the next project

---

## 🔭 Future Improvements

This lab is actively evolving. Planned additions include:

- [ ] Adding personal architecture diagrams for each project
- [ ] Writing post-mortems and learnings for each completed project
- [ ] Integrating cost estimates per project using Infracost
- [ ] Adding GitHub Actions workflows to validate Terraform configs on pull requests
- [ ] Building a simple static dashboard that tracks progress across all 20 projects
- [ ] Expanding Project 18 (Platform Engineering) with a self-service developer portal

---

## 🤝 Contributing

This is a personal learning repository, but feedback, suggestions, and improvements are genuinely welcome.

If you spot an error, have a better approach, or want to suggest an enhancement:

1. Fork the repository
2. Create a feature branch: `git checkout -b fix/your-description`
3. Commit your changes: `git commit -m "fix: describe what you changed"`
4. Push to your branch: `git push origin fix/your-description`
5. Open a Pull Request with a clear description of what you changed and why

Please keep contributions focused and well-documented.

---

## 🙌 Acknowledgements

A huge thank you to **[Olamide Kosile (@Mide69)](https://github.com/Mide69)** — the engineer and mentor who designed this entire project roadmap and made it available as a structured learning path.

Olamide put together a thoughtfully sequenced curriculum that takes you from deploying your first S3 bucket all the way to running chaos experiments and managing cloud costs at scale. The project structure, the progression, and the real-world scope of these exercises reflect serious engineering experience — and a genuine commitment to helping others grow in this field.

If you're a developer or student looking for a mentor-guided path into Cloud and DevOps, his work is a great place to start. Check out the original repository: [Mide69/AWS-Engineering-Project](https://github.com/Mide69/AWS-Engineering-Project).

---

## 📄 License

This repository is open-sourced under the [MIT License](LICENSE). You're free to use, adapt, and build on this work — just keep the attribution.

---

<div align="center">

**Built with curiosity and a lot of AWS bills** ☁️

[GitHub](https://github.com/ericgitau-tech) · [LinkedIn](https://linkedin.com/in/) · [AWS Certifications](#)

</div>
