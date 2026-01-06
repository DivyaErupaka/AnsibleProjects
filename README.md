
# Ansible Automation – Control Node Setup

This repository demonstrates the setup of an Ansible control node and managed nodes on AWS EC2, focusing on reliable installation, system preparation, and verification of configuration management tooling.

The project reflects real-world infrastructure setup practices, including OS-level dependency management and secure remote connectivity.

---

## 🔧 Environment
- Cloud Provider: AWS EC2
- OS: Ubuntu Linux
- Access Method: SSH (MobaXterm)
- Automation Tool: Ansible

---

## 📌 Implementation Overview

### 1. Infrastructure Preparation
- Provisioned separate EC2 instances for:
  - Ansible Control Node
  - Managed Nodes
- Established secure SSH connectivity using key-based authentication

### 2. System Preparation
- Updated OS package repositories to ensure access to latest stable packages
- Installed Python package management tools required for automation

### 3. Ansible Installation
- Installed Ansible using the native OS package manager for stability and compatibility
- Verified Ansible installation and version

---

## ✅ Validation
```bash
ansible --version
