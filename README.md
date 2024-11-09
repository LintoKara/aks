# aks
Microservice application deployments in AKS

The project revolves around the Kubernetes world and comprises 3 medium-complexity projects to build and deploy as per Industry standards that go right into a resume worth 6 months of experience. 
Projects cover the setup of a production-grade K8s cluster using Terraform, the GitOps approach to deploy microservices applications with a Database running in the cluster and Observability/Monitoring of the cluster using multiple industry tools.

Key Topics
1. Project Topics
2. Git Setup
3. Git Hub Actions
4. Code Scanning
5. AKS infra with Terraform

Project Plan :
Deploying Microservice Demo on Azure using AKS
1. Introduction
   This project includes deploying a Microservice Demo on Azure using AKS. This deployment will follow the key DevOps principles to ensure a robust, Scalable and secure setup
2.  Architecture Overview
    The application consists of several microservices communicating with each
  2.1 Architecture Diagram
  ![Atchitecture_diagram](https://github.com/user-attachments/assets/71fec3f2-9278-4e19-bd52-f43e69aeccc7)
  2.2 Protocols and Language Used in the Project
      This will be useful in the Code scanning since it uses various language for the application, and we need a scanning tool to support these applications
  ![image](https://github.com/user-attachments/assets/03e757e0-44c9-459f-b3f3-d79bdaa4838c)
  2.3 Application Screenshot
  ![image](https://github.com/user-attachments/assets/cb28404c-da35-4afc-bb07-f9b7ac218ea3)
3. DevOps principal Implementation
   3.1 Infrastructure As a Code (IaC)
         Tool: Terraform
         Objective: Define and deploy infrastructure using code to ensure reproducibility and version control
   3.2 Containerization
         Tool: Docker
         Objective: Containerize all microservices for consistent environments across development, testing, and production.
   3.3 CI/CD
         Tools: GitHub Actions or Azure DevOps
         Objective: Automate the build test and deploy process
   3.4 Azure Container Registry (ACR)
         Objective: Store and manage container images securely
   3.5 Helm for Package Management
         Objective: Use helm charts to manage Kubernetes Application deployments
   3.6 Network Security
         Objective: implement network policies, use Azure Firewall, and ensure secure communication between microservices
   3.7 Monitoring and Observability
         Tools: Azure Monitor, Prometheus, Grafana
         Objective: Monitor the health, performance, and logs of the application
   3.8 Scalability
         Objective: Ensure the application can scale out and in Based on the demands using Kubernetes autoscaling feature
   3.9 Resilience
         Objective: Design the system to handle failures gracefully, ensuring high availability
   3.10 Blue/Green or Canary Deployment
         Objective: Implement deployment strategies to minimize downtime and risk during updates.
   3.11 GitOps
         Tool: ArgoCD or Flux
   3.12 Container Security
         Tools: Azure Security Center, Aqya Security, Trivy
         Objective: Scan and secure container images to protect against vulnerabilities
   3.13 Code Scanning
         Tools: GitHub Code scanning, Sonarqube, Snyk
         Objective: Analyse the code for vulnerabilities and code quality issues before deployments
   3.14 Artifacts Management
         Tools: Azure Artifacts
         Objective: Manage and store builds artifacts, Including Helem charts, Docker Images, and other dependencies
   
   
   
         
   
   
       
      
   
   
