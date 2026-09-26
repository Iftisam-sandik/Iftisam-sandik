# Hi, I'm Ifti Sam Ibn Rahman 👋

### Server Administrator | Junior DevOps / Cloud Engineer

Computer Science graduate currently working in server administration and building hands-on experience in DevOps and cloud engineering.

I work with AWS infrastructure, Linux systems, Infrastructure as Code, configuration automation, CI/CD, containers, and observability. My focus is on building reliable environments where infrastructure, deployment, monitoring, logging, and automation work together as one complete system.

---

## 🛠 Core Technologies

**Cloud & Infrastructure**  
AWS EC2 · VPC · ALB · Auto Scaling · RDS · IAM · CloudWatch · Terraform

**Automation & CI/CD**  
Ansible · Git · GitHub · Jenkins · AWS CodePipeline · CodeBuild · CodeDeploy · GitHub Actions

**Containers & Systems**  
Docker · Docker Compose · Kubernetes · Linux · Nginx · Bash · Python

**Monitoring & Observability**  
Prometheus · Grafana · Loki · Grafana Alloy · Alertmanager · Node Exporter · cAdvisor · Blackbox Exporter · mysqld_exporter

**Applications & Databases**  
Node.js · Express.js · React · MySQL · PostgreSQL · Redis · Kafka

---

## 🚀 Selected DevOps Projects

### Production-Style AWS Observability Platform

Built and automated a 4-node AWS environment for a Dockerized React, Node.js, and MySQL application behind an Application Load Balancer. Implemented infrastructure and configuration automation with Terraform and Ansible, full-stack monitoring with Prometheus and Grafana, centralized logging with Alloy and Loki, Grafana RBAC, and Alertmanager notifications.

**Highlights**
- 11/11 healthy monitoring targets
- Zero Terraform drift
- Fully idempotent Ansible automation across all servers

**Stack:** AWS · Terraform · Ansible · Docker · Prometheus · Grafana · Loki · Alloy · Alertmanager · MySQL

[View Repository](https://github.com/Iftisam-sandik/Library-Management-System)

---

### Highly Available 3-Tier AWS Application with Auto Scaling & CI/CD

Designed and deployed a highly available 3-tier AWS architecture using a custom VPC, Application Load Balancer, private frontend and backend Auto Scaling environments, and private RDS MySQL. Automated application delivery from GitHub through AWS CodePipeline, CodeBuild, and CodeDeploy with Blue/Green releases, monitoring, notifications, and secure secret management.

**Highlights**
- Validated Blue/Green deployments with versioned production releases
- Implemented Auto Scaling self-healing with automated deployment to newly launched instances
- Completed final validation with 7 passed and 0 failed checks

**Stack:** AWS · VPC · ALB · Auto Scaling · RDS · CodePipeline · CodeBuild · CodeDeploy · CloudWatch · SNS · SSM

[View Repository](https://github.com/Iftisam-sandik/aws-3tier-autoscaling-cicd)

---

### AWS Distributed Microservices Architecture

Designed and deployed a distributed microservices environment on AWS using multiple EC2 instances, Nginx, and load-balanced traffic routing. Integrated MySQL, Redis, BullMQ, and Kafka to support persistent storage, caching, background processing, and event-driven communication while maintaining service isolation.

**Highlights**
- Deployed multiple private application servers behind centralized traffic routing
- Integrated MySQL, Redis queues/cache, and Kafka-based event processing
- Implemented CI/CD to private application servers using a self-hosted GitHub Actions runner

**Stack:** AWS · EC2 · VPC · Nginx · Node.js · MySQL · Redis · BullMQ · Kafka · ZooKeeper · GitHub Actions · CloudWatch

[View Repository](https://github.com/Iftisam-sandik/ems-microservices-aws)

---

### Terraform AWS VPC Bastion Infrastructure

Provisioned a secure AWS networking environment entirely with Terraform, including a custom VPC, public and private subnets, routing, security groups, a bastion host, and private EC2 infrastructure. Designed the access model so private workloads remained inaccessible directly from the Internet while administrative access was routed through the bastion host.

**Highlights**
- Provisioned the complete AWS network and compute environment using Infrastructure as Code
- Kept private EC2 infrastructure isolated from direct public access
- Enforced controlled SSH administration through a dedicated bastion host

**Stack:** AWS · Terraform · VPC · EC2 · Security Groups · Linux · SSH

[View Repository](https://github.com/Iftisam-sandik/terraform-aws-vpc-bastion-ec2)

---

### Kubernetes Todo App on AWS EC2

Containerized a Todo web application with Docker and Nginx, published the image to Docker Hub, and deployed it on a single-node Kubernetes cluster running on AWS EC2. Built the cluster using kubeadm, containerd, and Flannel CNI and managed the application through Kubernetes workloads and networking resources.

**Highlights**
- Completed the full Docker → Docker Hub → Kubernetes deployment workflow
- Built a Kubernetes cluster using kubeadm, containerd, and Flannel networking
- Deployed the application in a dedicated namespace and exposed it through a Kubernetes Service

**Stack:** AWS EC2 · Docker · Docker Hub · Kubernetes · kubeadm · containerd · Flannel · Nginx · Linux

[View Repository](https://github.com/Iftisam-sandik/kubernetes-todo-app)

---

## 🎯 Current Focus

- AWS architecture and cloud infrastructure
- Infrastructure as Code with Terraform
- Configuration management with Ansible
- Kubernetes and container orchestration
- Monitoring, logging, and observability
- CI/CD and deployment automation
- Linux server administration

---

## 📫 Connect With Me

**Email:** sandik55575@gmail.com  
**GitHub:** [Iftisam-sandik](https://github.com/Iftisam-sandik)

---

I'm currently focused on growing as a **DevOps / Cloud Engineer** by combining hands-on infrastructure projects with real-world server administration experience.
