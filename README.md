# Homelab Environment Documentation

This repository documents the architecture, services, configuration, and infrastructure of my personal homelab.  
The environment is built for learning, testing, and developing skills in networking, containers, virtualization, IaC, and reverse proxy management.  
It also serves as a groundwork for future projects, including CDN-style caching labs and advanced DevOps workflows.

---

## 📦 Infrastructure Overview

### **Hardware**
- **System:** HP Omen
- **Purpose:** Dedicated homelab host

### **Hypervisor**
- **Proxmox VE**
- Managing multiple VMs for containerization, development, and sandbox testing.

### **Primary VM**
- **OS:** Ubuntu Server (Docker host)
- **Role:** Runs all containerized services in this documentation
- **Container Tools:**
  - Docker Engine
  - Docker Compose
  - Portainer CE (Container management UI)

### **Reverse Proxy**
- **Nginx Proxy Manager**
- Provides SSL, routing, and public access to internal services.

---

## 🏗️ Architecture Diagram

WORK IN PROGRESS

