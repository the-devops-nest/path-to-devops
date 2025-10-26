// ...existing code...
# 🚀 DevOps Training Program — 4‑Month Hands‑On Curriculum

Concise, demo-ready overview for instructors and demo audiences. This course is designed to take learners from core DevOps fundamentals to deploying a secure, observable application on AWS EKS with an end‑to‑end CI/CD pipeline.

## Quick elevator pitch (for demo)
A practical 4‑month program that teaches DevOps culture, tools, and workflows through weekly hands‑on labs and real projects. Learners will build and ship an application using Git → CI/CD → Docker → Terraform → EKS, with monitoring and security built in.

## Who is this for?
- Junior developers or operations engineers transitioning to DevOps
- DevOps learners who want a project-based curriculum
- Teams wanting a reproducible training plan to upskill staff

## Learning outcomes
By program end learners will be able to:
- Apply DevOps principles and workflows
- Build CI/CD pipelines (Jenkins / GitHub Actions)
- Containerize apps with Docker and Compose
- Provision AWS infra with Terraform
- Run workloads on Kubernetes (EKS) and Helm
- Implement monitoring, logging and basic DevSecOps checks
- Deliver a final end-to-end project

## 4‑Month Roadmap (high level)
Month 1 — Fundamentals
- Git, Linux, Bash, Docker, CI/CD basics (Jenkins/GitHub Actions)

Month 2 — Cloud & IaC
- AWS core services, Terraform, multi‑tier infra, VPC, S3, RDS

Month 3 — Kubernetes & Observability
- EKS, Helm, Prometheus/Grafana, logging (ELK/Fluent)

Month 4 — DevSecOps, Data & Final Project
- Security in pipelines, Databricks overview, final project build & showcase

## Demo script (10–15 min)
1. 0:00–0:60 — Program elevator pitch and outcomes (use slide)
2. 1:00–3:00 — Curriculum walkthrough (highlight month milestones)
3. 3:00–7:00 — Live demo: show repo, key files, and one short live command
   - Show Dockerfile + docker build/run OR Terraform plan (local)
4. 7:00–10:00 — Final project brief: architecture diagram and delivery checklist
5. 10:00–12:00 — Q&A and next steps for learners

## Live demo checklist (prepare before session)
- AWS credentials configured on demo machine (or show screenshots)
- Docker installed and running: docker --version
- kubectl and eksctl (or minikube) installed: kubectl version --client
- Terraform installed: terraform -version
- Jenkins or GitHub Actions pipeline files present for quick preview
- Example repo branch with a small app ready (avoid long builds)

Sample quick commands to show in demo:
- Show Docker build: docker build -t devops-demo:latest ./demo-app
- Show Terraform plan (in safe mode): terraform init && terraform plan
- Show kubectl resources: kubectl get pods --namespace demo

## Repo structure (what to show)
- /labs — step‑by‑step lab guides and starter code
- /terraform — example modules and sample infra code
- /k8s — manifest examples and Helm charts
- /ci — Jenkinsfiles / GitHub Actions workflows
- /final-project — architecture, checklist, evaluation rubric

## How to run a sample lab (2‑minute flow)
1. Clone the repo and open the lab folder:
   - git clone <repo> && cd path-to-devops/labs/01-git
2. Follow the lab README (each lab is self-contained)
3. Use provided scripts for quick verification:
   - ./scripts/verify-lab.sh

## Presentation tips
- Focus on outcomes and practical skills, not tool minutiae
- Use short live demos (30–90s) to illustrate flow
- Prepare screenshots for long-running operations (Terraform apply, EKS creation)
- End with the final project architecture and how learners will be assessed

## Resources & references
- Official docs: Terraform, Kubernetes, Docker, AWS
- Recommended quick reads: The Phoenix Project, Continuous Delivery
- Starter templates included in /templates

## Contact & Next steps
- Use the /labs folder for guided practice
- Instructor notes and slide deck stored in /docs
- For changes or additions open a PR against this repo

// ...existing code...
{ changed code }
// ...existing code...# 🚀 DevOps Training Plan  

This repository contains a **4-month structured DevOps Training Program** with detailed class-by-class agendas, labs, and projects.  

---

## 📖 Table of Contents  
- [Month 1: Core Fundamentals](#-month-1-core-fundamentals)  
- [Month 2: Cloud & Infrastructure as Code](#-month-2-cloud--infrastructure-as-code)  
- [Month 3: Kubernetes on AWS & Observability](#-month-3-kubernetes-on-aws--observability)  
- [Month 4: DevSecOps, Data, and Final Project](#-month-4-devsecops-data-and-final-project)  
- [Final Outcome](#-final-outcome)  

---

## 📅 Month 1: Core Fundamentals  

### Weekend 1: DevOps & Git  
- **Class 1:** Introduction to DevOps  
  * Principles, culture, lifecycle, case study  
- **Class 2:** Git Fundamentals  
  * Commands, remote repos, first Git project  

### Weekend 2: Linux & Shell Scripting  
- **Class 3:** Essential Linux Commands  
  * Navigation, permissions, text processing  
- **Class 4:** Bash Scripting  
  * Variables, loops, automation, lab task  

### Weekend 3: Docker Basics 🐳  
- **Class 5:** Introduction to Containers & Docker Core Concepts  
- **Class 6:** Writing Dockerfiles, Docker Compose (multi-container apps, lab)  

### Weekend 4: CI/CD Foundations ⚙️  
- **Class 7:** CI/CD Concepts, Jenkins & GitHub Actions setup  
- **Class 8:** Jenkins Pipelines (stages, Docker integration, CI/CD pipeline lab)  

---

## 📅 Month 2: Cloud & Infrastructure as Code  

### Weekend 5: AWS Fundamentals ☁️  
- **Class 9:** IAM, EC2, Key Pairs, Security Groups  
- **Class 10:** VPC, S3, Hosting static site (Lab: VPC + EC2 + S3 website)  

### Weekend 6: Terraform Basics 🌍  
- **Class 11:** IaC Concepts, Terraform workflow (init, plan, apply)  
- **Class 12:** Terraform Variables, Outputs, Modules (Lab: Provision AWS infra)  

### Weekend 7: Advanced AWS Services  
- **Class 13:** Load Balancers, Auto Scaling, RDS basics  
- **Class 14:** Hands-on Project: Deploy a 3-tier app using Terraform  

### Weekend 8: Kubernetes Fundamentals ☸️  
- **Class 15:** Kubernetes Concepts (Pods, Services, Deployments)  
- **Class 16:** kubectl labs, Minikube hands-on, ConfigMaps & Secrets  

---

## 📅 Month 3: Kubernetes on AWS & Observability  

### Weekend 9: Kubernetes on AWS (EKS)  
- **Class 17:** EKS setup, cluster basics  
- **Class 18:** Deploying apps to EKS, Ingress, Services  

### Weekend 10: Helm & Advanced K8s ⛵  
- **Class 19:** Helm charts, releases, templates  
- **Class 20:** Lab – Deploy multi-container app using Helm on EKS  

### Weekend 11: Monitoring & Logging 📊  
- **Class 21:** AWS CloudWatch (metrics, logs, alarms, dashboards)  
- **Class 22:** Logging with Fluent/ELK basics, Monitoring with Prometheus + Grafana  

### Weekend 12: Observability Tools 🔎  
- **Class 23:** Datadog – setup and dashboards  
- **Class 24:** Dynatrace – monitoring pipelines, real-world example  

---

## 📅 Month 4: DevSecOps, Data, and Final Project  

### Weekend 13: DevSecOps 🔐  
- **Class 25:** Security in CI/CD (SAST, DAST, Secrets mgmt.)  
- **Class 26:** Hands-on – Integrate security scans into Jenkins pipeline  

### Weekend 14: Databricks & Big Data Integration 📊  
- **Class 27:** Introduction to Databricks & Spark basics  
- **Class 28:** Building a pipeline with Databricks component  

### Weekend 15: Final Project (Build) 🏗️  
- **Class 29:** End-to-end pipeline (Git → Jenkins → Docker → Terraform → EKS)  
- **Class 30:** Add monitoring, security, and Databricks integration  

### Weekend 16: Final Project (Showcase & Review) 🎤  
- **Class 31:** Project Presentations & Review of Key Concepts  
- **Class 32:** Best Practices, Career Guidance, Future Trends in DevOps  

---

## 🎯 Final Outcome  
By the end of this program, learners will:  
- Understand DevOps principles, tools, and practices  
- Build real-world CI/CD pipelines  
- Deploy infrastructure on AWS with Terraform  
- Run applications on Kubernetes (EKS)  
- Implement observability with monitoring & logging tools  
- Integrate security into pipelines (DevSecOps)  
- Complete an **end-to-end DevOps Project**  

---
