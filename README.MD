# SIG SERVICE – Vault Security Lab

## Overview

This project is a DevSecOps and cybersecurity lab developed during my internship at **SIG SERVICE**.

The objective is to explore secure infrastructure deployment and centralized secrets management by integrating **HashiCorp Vault** into an Odoo ERP environment.

The lab demonstrates how sensitive configuration data and credentials can be managed securely using Vault, while deploying and orchestrating services across a containerized infrastructure.

## Architecture

The infrastructure is composed of the following components:

- **HashiCorp Vault:** Centralized secrets management and secure storage of sensitive information.
- **Odoo:** ERP application.
- **PostgreSQL:** Database management for Odoo.
- **Traefik:** Reverse proxy for application traffic routing.
- **Docker Compose:** Container orchestration and service management.

## Technologies Used

| Technology | Purpose |
|---|---|
| HashiCorp Vault | Secrets management |
| Docker | Containerization |
| Docker Compose | Service orchestration |
| Odoo | ERP application |
| PostgreSQL | Database management |
| Traefik | Reverse proxy |
| Linux | Infrastructure environment |

## Key Features & Objectives

- Deploy and configure HashiCorp Vault.
- Centralize sensitive information using Vault.
- Integrate secrets management into an Odoo environment.
- Deploy and manage infrastructure services using Docker Compose.
- Configure Traefik as a reverse proxy.
- Reduce exposure of sensitive credentials in application configurations.
- Explore secure communication between infrastructure components.

## Security Considerations

This project focuses on applying security principles to infrastructure deployment, particularly centralized secrets management and credential protection.

Sensitive credentials, Vault tokens, and database passwords must never be committed to version control.

The environment is designed for laboratory and educational purposes.

## Author

**Mohamed Mehbarki**

Cybersecurity Engineering Student – USTHB


*Developed during a cybersecurity internship at SIG SERVICE.*