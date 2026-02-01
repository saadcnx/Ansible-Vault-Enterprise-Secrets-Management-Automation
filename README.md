🔐 Secure Secrets Management with Ansible Vault  
**Production-Ready Infrastructure Automation | DevOps | Security**

---

## 📌 Overview
Enterprise-grade **secrets management** using Ansible Vault.  
Simulates **real-world production scenarios** where sensitive data — database credentials, API keys, SSL paths, tokens — must be secured across **Dev / Staging / Production** environments.

Perfect for **DevOps, Cloud, and Infrastructure Automation roles**.  

---

## 🚀 Key Highlights
- **Secure Encryption**: Protect secrets in version control  
- **Multi-Environment Support**: Dynamic env selection (dev/staging/prod)  
- **Vault IDs**: Enterprise-level vault password management  
- **Security Best Practices**: `no_log`, restricted permissions, masking secrets  
- **Automation Workflows**: Production-ready playbooks  
- **Backup & Recovery**: Automated vault backups & restoration  
- **Validation & Troubleshooting**: Playbooks for diagnostics, type checks, and assertions  

---

## 🛠️ Tech Stack
- **Ansible & Ansible Vault**  
- **Linux (Ubuntu)**  
- **YAML & Bash Scripting**  
- **Infrastructure as Code (IaC) Principles**  

---
### 🔐 Features

**Secrets Encryption**

- **Database credentials, API keys, tokens, SSL paths**
- **Prevents plaintext exposure in repos**

**Multi-Environment Automation**

- **Environment-specific vault files**
- **Dynamic configuration using extra vars**

**Vault IDs (Enterprise)**

- **Separate vault passwords per environment**
- **Secure production deployments**

**Security Best Practices**

- **no_log: true for sensitive tasks**
- **Restricted file permissions (0600)**
- **Secrets never logged or exposed**

**Troubleshooting & Validation**

- **Vault diagnostics & validation playbooks**
- **Type checks, interpolation & integration tests**

**Backup & Recovery**

- **Automated vault backups with timestamps**
- **Safe restoration workflows**

---

### 🎯 Real-World Applications

- **Securing CI/CD pipelines**
- **Cloud API key & database credential management**
- **Infrastructure automation at scale**
- **Compliance-ready automation (SOC2, PCI-DSS, GDPR)**

---
🧩 Skills Demonstrated

Ansible, Secrets Management, IaC, Linux SysAdmin, DevOps Security, Multi-Environment Deployment, Configuration Management, Secure Automation Design
---
## 📁 Project Structure
```text
ansible-vault-lab/
├── inventory/          # Hosts & static inventory
├── playbooks/          # Modular automation workflows
├── vault_files/        # Encrypted secrets per environment
├── scripts/            # Vault inventory & backup scripts
└── backups/            # Backup manifests & recovery
