# **AWS DevOps Project**

This repository demonstrates a two-task DevOps assignment using **AWS, Terraform, GitHub Actions, and Kubernetes**.  
It showcases CI/CD automation, infrastructure as code (IaC), and security integration.

---

## **Repository Structure**
```
AWS-DevOps-Project/
│
├── Task1-CodePipeline/   # Terraform-based AWS CodePipeline setup
└── Task2-DevSecOps/      # CI/CD with security scanning & Sealed Secrets
```

---

## **Task 1: AWS CodePipeline using Terraform**

- **Objective**: Provision AWS CodePipeline for automated build and deployment.
- **Key Components**:
  - **Source**: GitHub
  - **Build**: AWS CodeBuild
  - **Deploy**: AWS CodeDeploy/EC2
- **Infrastructure**: Defined entirely using Terraform for reproducibility.

**Pipeline Workflow**:
1. Code pushed to GitHub triggers the pipeline.
2. CodeBuild builds and tests the application.
3. CodeDeploy deploys the build to EC2 instances.

---

## **Task 2: DevSecOps Integration**

- **Objective**: Implement a CI/CD pipeline with integrated security scanning.
- **Tech Stack**: GitHub Actions, Docker, Terraform, Kubernetes.
- **Security Tools**:
  - **tfsec**: Static analysis for Terraform code.
  - **Trivy**: Docker image vulnerability scanning.
  - **Sealed Secrets**: Secure Kubernetes secret management.
- **Workflow**:
  1. Code changes trigger GitHub Actions.
  2. Build, test, and security scans run automatically.
  3. Infrastructure changes applied via Terraform.
  4. Application deployed to Kubernetes.

---

## **Architecture Diagram**
*(Add your architecture diagram image here, e.g. `![Architecture](diagram.png)`)*

---

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/Monalisha18/AWS-DevOps-Project.git
   ```
2. Navigate to the required task folder:
   ```bash
   cd Task1-CodePipeline   # or cd Task2-DevSecOps
   ```
3. Follow the instructions inside each folder’s README.

---

## **Key Learnings**
- Automated deployments reduce manual effort and errors.
- Integrated security scanning ensures safe deployments.
- IaC with Terraform enables version-controlled, reproducible infrastructure.
- Kubernetes and Sealed Secrets improve scalability and secret management.

---

## **GitHub Links**
- [Task 1 – CodePipeline Demo](https://github.com/Monalisha18/Codepipeline-demo)
- [Task 2 – DevSecOps Task](https://github.com/Monalisha18/devsecops-task2)
