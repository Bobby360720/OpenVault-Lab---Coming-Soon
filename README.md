# 🛡️ OpenVault Lab  -*Comming Soon* 

**A Privacy-First DevSecOps Home Lab for Cloud Security Architecture**

OpenVault Lab is a personal cloud infrastructure project designed to showcase advanced skills in cloud architecture, cybersecurity, and DevSecOps. Built entirely on open-source tools and principles of data sovereignty, this lab simulates a real-world, enterprise-ready cloud environment with zero-trust networking, GitOps automation, secure application development, and threat monitoring.

## 🔍 Project Goals

- Build and document a production-grade open-source cloud environment
- Demonstrate CTO-level strategic design and Security Architect implementation
- Create a secure deployment pipeline with GitOps, containers, and CI/CD
- Develop and deploy a custom full-stack application (Political Stat Tracker)
- Practice infrastructure hardening, network segmentation, and threat detection

---

## 🧱 Core Architecture

| Layer               | Tools Used                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| Hypervisor          | Proxmox VE                                                                 |
| Network & Firewall  | pfSense / OPNsense, VLANs, WireGuard                                        |
| Management & Access | Ansible, Keycloak, Authelia, Vault                                          |
| Monitoring & SIEM   | Prometheus, Grafana, Wazuh, Loki, Fluent Bit                                |
| Automation          | GitHub Actions, Drone CI, Terraform, GitOps pipelines                      |
| Container Runtime   | Docker, microK8s, NGINX, Traefik                                            |
| Data & Identity     | PostgreSQL, TLS Internal CA, JWT Auth, Encrypted Backups                    |

---

## 🗳️ Featured App: Political Stat Tracker

A secure, full-stack web app that lets users track political representatives like fantasy sports stats. Built with FastAPI (or Express.js) and Svelte (or React), and deployed in a segmented, zero-trust namespace.

---

## 🛡️ Security Highlights

- 🧩 Zero Trust network segmentation
- 🔐 Internal certificate authority (TLS Everywhere)
- 👥 Role-Based Access Control + SSO (Keycloak/Auth Proxy)
- 🛠️ Infrastructure-as-Code for reproducibility
- 🔍 Real-time telemetry and SIEM alerting
- 🧪 Penetration testing & hardening baked into design



