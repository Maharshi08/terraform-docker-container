# Terraform Docker Demo

## 🎯 Task 3: Infrastructure as Code (IaC) with Terraform

### ✅ Objective:
Provision a local Docker container using Terraform.

---

### 📦 Tools Used:
- [Terraform](https://www.terraform.io/)
- [Docker](https://www.docker.com/)

---

### 📁 Files:
- `main.tf` – Terraform configuration file
- `README.md` – Project overview
- `terraform.log` (optional) – Execution logs

---

### 📌 Steps Performed:

1. **Used Docker provider in Terraform**
2. **Wrote Terraform code to pull an nginx image and create a container**
3. **Ran `terraform init`, `terraform plan`, and `terraform apply`**
4. **Verified container creation and port mapping**
5. **Destroyed the infrastructure using `terraform destroy`**
6. **Checked Terraform state using `terraform state list`**

---

### 🚀 How to Run

Make sure Docker and Terraform are installed on your system.

```bash
# Initialize the project
terraform init

# Preview changes
terraform plan

# Apply configuration
terraform apply

# Destroy resources
terraform destroy
