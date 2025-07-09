# Three-tier-application

![architecture](https://github.com/user-attachments/assets/4177ee8c-2e1f-456e-8e83-01f0da133e7f)

Here's a professional and concise GitHub repository description and README section you can use for your **Three-tier application deployed on AWS using Terraform**:

---

### 🔰 GitHub Repository Description:

> Infrastructure-as-Code (IaC) project to deploy a scalable and secure Three-Tier Web Application architecture on AWS using Terraform.

---

### 📝 README Overview (to add in `README.md`):

````markdown
# 🏗️ Three-Tier Application on AWS using Terraform

This project automates the deployment of a Three-Tier Web Application architecture on AWS using **Terraform**, following Infrastructure-as-Code (IaC) best practices.

## 📌 Architecture Overview

The architecture consists of:
- **Frontend Tier**: Hosted on public EC2 instances (Web Layer)
- **Application Tier**: Private EC2 instances running app logic (App Layer)
- **Database Tier**: AWS RDS in a private subnet (DB Layer)

### 🔐 Security:
- Each tier is deployed in its own **subnet**.
- Communication between layers is managed via **Security Groups** and **NACLs**.
- Uses **public and private subnets** in multiple Availability Zones for high availability.

## ⚙️ Technologies Used
- **Terraform**
- **AWS EC2, RDS, VPC, Security Groups, Subnets**
- **Bash (for provisioning)**
- **Linux (Amazon AMI)**

## 🚀 Deployment

To deploy the infrastructure:

```bash
# Initialize Terraform
terraform init

# Preview changes
terraform plan

# Apply the configuration
terraform apply
````

## 📁 Project Structure

```
├── frontend.tf        # Web Tier EC2 instances
├── app.tf             # App Tier EC2 instances
├── db.tf              # RDS Database instance
├── network.tf         # VPC, Subnets, Route Tables
├── security.tf        # Security Groups for each tier
├── variables.tf       # Variables used across modules
├── outputs.tf         # Output values after apply
└── main.tf            # Terraform main configuration
```

## ✅ Outcomes

* Fully functional three-tier architecture with isolated layers.
* Demonstrates practical knowledge of **Terraform modules**, **state management**, and **secure AWS architecture**.
* Can be extended with **Load Balancers**, **Auto Scaling**, or **Monitoring (CloudWatch/Prometheus)**.

## 🧑‍💻 Author

**Mahir Sunil Dasare**
[LinkedIn](https://www.linkedin.com/in/mahir-dasare/) | [GitHub](https://github.com/Mahir0010)

---

⭐ If you found this useful, feel free to star the repo!

```

---

