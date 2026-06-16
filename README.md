<div align="center">

# ☁️ Azure 2-Tier Infrastructure Deployment with Terraform

### 🚀 Automating Azure Infrastructure using Infrastructure as Code (IaC)

![Azure](https://img.shields.io/badge/Azure-Cloud-blue?style=for-the-badge\&logo=microsoftazure)
![Terraform](https://img.shields.io/badge/Terraform-IaC-purple?style=for-the-badge\&logo=terraform)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-orange?style=for-the-badge\&logo=linux)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge\&logo=mysql)

</div>

---

## 📖 About The Project

This project showcases the deployment of a **2-Tier Application Architecture on Microsoft Azure** using **Terraform Infrastructure as Code**.

The infrastructure provisions a complete cloud environment consisting of an **Application Layer (VM)** and a **Database Layer (Azure MySQL)** while automating networking, security, and resource management.

> 💡 Build Once • Deploy Anywhere • Manage as Code

---

## ✨ Project Highlights

🔹 Fully Automated Azure Infrastructure

🔹 Infrastructure as Code using Terraform

🔹 Azure Virtual Machine Deployment

🔹 Azure Database for MySQL Integration

🔹 Secure Networking Configuration

🔹 Reusable & Scalable Terraform Modules

🔹 Cloud Best Practices Implementation

🔹 Production-Ready Foundation

---

## 🏗️ Architecture

```text
                     🌐 Internet
                           │
                           ▼
                    Public IP Address
                           │
                           ▼
        ┌─────────────────────────────┐
        │     Azure Linux VM          │
        │  Frontend + Backend Layer   │
        └──────────────┬──────────────┘
                       │
                       ▼
        ┌─────────────────────────────┐
        │ Azure Database for MySQL    │
        │       Database Layer        │
        └─────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Category        | Technology            |
| --------------- | --------------------- |
| Cloud           | Microsoft Azure       |
| IaC             | Terraform             |
| Compute         | Azure Virtual Machine |
| Database        | Azure MySQL           |
| Networking      | VNet, Subnet, NSG     |
| OS              | Ubuntu Linux          |
| Version Control | Git & GitHub          |

---

## 📂 Repository Structure

```bash
📦 azure-2tier-terraform
 ┣ 📂 modules
 ┃ ┣ 📂 networking
 ┃ ┣ 📂 compute
 ┃ ┗ 📂 database
 ┃
 ┣ 📜 provider.tf
 ┣ 📜 variables.tf
 ┣ 📜 main.tf
 ┣ 📜 outputs.tf
 ┣ 📜 terraform.tfvars
 ┗ 📜 README.md
```

---

## ⚙️ Deployment Workflow

```bash
terraform init
terraform validate
terraform plan
terraform apply
```

### 🔹 Initialize

Downloads required providers.

### 🔹 Validate

Checks Terraform configuration syntax.

### 🔹 Plan

Previews infrastructure changes.

### 🔹 Apply

Deploys Azure resources automatically.

---

## 🚀 Azure Resources Created

✅ Resource Group

✅ Virtual Network (VNet)

✅ Subnet

✅ Public IP

✅ Network Interface

✅ Network Security Group

✅ Linux Virtual Machine

✅ Azure Database for MySQL

---

## 🔐 Security Features

```yaml
✔ Network Security Groups
✔ Controlled Inbound Traffic
✔ Database Isolation
✔ Secure Resource Management
✔ Infrastructure Version Control
```

---

## 🎯 Learning Outcomes

### Terraform

* Resource Provisioning
* Variables & Outputs
* State Management
* Modular Architecture

### Azure

* Cloud Networking
* Virtual Machines
* Database Services
* Security Implementation

### DevOps

* Infrastructure Automation
* Infrastructure as Code
* Cloud Deployment Practices
* GitOps Fundamentals

---

## 📊 Project Outcomes

🚀 Reduced Manual Deployment Effort

⚡ Faster Infrastructure Provisioning

🔄 Repeatable Deployments

📈 Improved Scalability

🛡️ Better Security & Resource Management

---

## 🔮 Future Enhancements

* Azure Load Balancer
* Application Gateway
* GitHub Actions CI/CD
* Azure Key Vault
* Docker Integration
* AKS Deployment
* Monitoring & Logging

---


<div align="center">

### 🌟 Infrastructure as Code • Automation • Cloud Engineering

**Built with ❤️ using Terraform & Microsoft Azure**

</div>

## Documented and Done by Saibaba Kola
