# Devops Engineer
- Skilled DevOps Engineer with 3.10 years of hands-on experience architecting/ automating and optimizing mission-critical deployments over extensive infrastructure. Proficient with infrastructure provisioning tools, and in developing CI/CD pipelines.


### Education
BCA Bachelor of Computer Applications | SRI VENKATESWARA UNIVERSITY 2020-OCT



### 🛠️ Technologies & Tools

- Cloud: AWS (EC2, S3, Lambda, EKS, Cloudfront , IAM , Route53 , Rds , Fargate , ECR , ECS etc.)

- Infrastructure as Code: Terraform, AWS CloudFormation.

- Containers & Orchestration: Docker, Kubernetes, Helm.

- CI/CD:  Jenkins, Sonarqube , Trivy , Jira , Artifact-Hub , Argocd.

- Monitoring & Logging: Prometheus, Grafana, ELK Stack.

- Scripting & Automation: Bash.

- Version Control: Git, GitHub.

### work experience
Devops Engineer @ TCS Tata conscultancy servicies (_December 2020 - _November 2024)

### 📂 Projects @ TCS (from )

###  Deployed Jupyter-hub on prem cluster using helm charts

- I deployed JupyterHub on an on-premises Kubernetes cluster using Helm charts to provide a scalable, multi-user Jupyter Notebook environment. First, I ensured the cluster was properly configured with role-based access control (RBAC) and persistent storage for user data. Then, I used the official JupyterHub Helm chart, customized its values.yaml file to configure authentication, resource limits, and storage, and deployed it with helm install. Post-deployment, I set up Ingress and SSL certificates to allow secure access. Finally, I monitored and fine-tuned performance using Prometheus and Grafana, ensuring stability and scalability for multiple users.

### Deployed Selinium-Grid on prem cluster using helm charts

- I deployed Selenium Grid on an on-premises Kubernetes cluster using Helm charts to enable scalable, distributed test execution. First, I configured the Kubernetes cluster with appropriate resource allocations and network policies. Then, I customized the Selenium Grid Helm chart (values.yaml) to define the hub, browser nodes (Chrome/Firefox), and session handling settings. Using helm install, I deployed the grid and verified node connectivity. To enable external access, I configured Ingress and persistent storage for logs and test reports. Finally, I integrated it with CI/CD pipelines (e.g., Jenkins) for automated parallel testing, ensuring efficient test execution.

### POS System Modernization: Migrating JavaPOS to Kubernetes

- As part of a team, we worked on modernizing a JavaPOS system by migrating it from a monolithic architecture to a microservices-based application deployed on Kubernetes. We started by analyzing the existing monolithic codebase and breaking it down into modular Spring Boot microservices for core functionalities like billing, inventory, and payments. Each microservice was containerized using Docker and deployed on Kubernetes for scalability and fault tolerance. The team implemented CI/CD pipelines using Jenkins, GitHub Actions, and ArgoCD to automate builds, testing, and deployments. We integrated Istio for service-to-service security and Kafka for asynchronous event-driven communication. Additionally, Prometheus, Grafana, and ELK Stack were used for monitoring and logging, ensuring reliability and performance.

# Tools & Technologies Used:

- Microservices & Development: Java (Spring Boot), REST APIs, gRPC
- Containerization & Orchestration: Docker, Kubernetes, Helm
- CI/CD & Automation: Jenkins, GitHub Actions, ArgoCD
- Service Mesh & Security: Istio, HashiCorp Vault
- Message Broker: Apache Kafka, RabbitMQ
- Monitoring & Logging: Prometheus, Grafana, ELK Stack (Elasticsearch, Logstash, Kibana)
- Storage & Databases: PostgreSQL, MongoDB, Redis

# This modernization enhanced scalability, maintainability, and deployment efficiency, allowing for seamless feature updates and high availability of the POS system.

### Terraform-Powered AWS Infrastructure: From Legacy Imports to Scalable, Automated Cloud Deployments

- As part of a team, we focused on infrastructure automation and modernization using Terraform on AWS, streamlining both existing infrastructure imports and new resource provisioning. Our goal was to enhance scalability, reliability, and operational efficiency while maintaining GitOps best practices.

- We started by importing legacy AWS resources such as EC2 instances, VPCs, Route 53 records, and security groups into Terraform’s state using terraform import, ensuring infrastructure consistency and version control. This allowed us to manage existing cloud resources declaratively without disrupting production workloads.

- For new infrastructure, we developed modular Terraform configurations to provision EKS clusters (with autoscaling worker nodes and IAM integration), EC2 instances (with optimized AMIs), serverless Lambda functions, and Route 53 DNS records for domain management. We leveraged Terraform workspaces to manage multiple environments (dev, staging, production) seamlessly.

- To ensure reliability and security, we integrated Terraform with AWS S3 (backend state) and DynamoDB (state locking) for safe multi-user collaboration. CI/CD workflows were implemented using GitHub Actions and Terraform Cloud, enabling automated deployments with policy enforcement and drift detection. Additionally, we incorporated AWS ALB for ingress traffic management, IAM policies for access control, and CloudWatch for proactive monitoring.

# Key Technologies & Tools:

- Infrastructure as Code (IaC): Terraform (modular approach)
- AWS Services Used: EKS, EC2, Route 53, Lambda, VPC, IAM, ALB
- CI/CD & Automation: GitHub Actions, Terraform Cloud, AWS CodePipeline
- State Management & Security: AWS S3 (Terraform backend), DynamoDB (state locking), IAM roles
- Monitoring & Logging: AWS CloudWatch, Prometheus, Grafana
- Networking: VPC, Subnets, Security Groups, Route 53

# By leveraging Terraform’s declarative approach, we transformed a fragmented, manually managed AWS environment into a scalable, automated, and version-controlled infrastructure, accelerating deployments and improving operational efficiency. 🚀


### 📂 Projects @ Personnel

###  Multi-Region Highly Available Web App: Built with Terraform & AWS
