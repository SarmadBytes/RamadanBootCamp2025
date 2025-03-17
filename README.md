# OSFP DevOps BootCamp - Ramadan 2025

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-1.32-blue)](https://kubernetes.io/)
[![Docker](https://img.shields.io/badge/Docker-Latest-blue)](https://www.docker.com/)
[![GitLab](https://img.shields.io/badge/GitLab-Self--Hosted-orange)](https://about.gitlab.com/)
[![MicroK8s](https://img.shields.io/badge/MicroK8s-1.32-brightgreen)](https://microk8s.io/)

## 📋 Table of Contents
- [Overview](#overview)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation Guides](#installation-guides)
- [Deployments](#deployments)
- [Monitoring](#monitoring)
- [CI/CD Integration](#cicd-integration)
- [Community](#community)
- [Previous Bootcamps](#previous-bootcamps)
- [License](#license)

## 🚀 Overview

Welcome to the **Ramadan DevOps Bootcamp 2025**, an intensive online training program designed to help you build a strong foundation in **DevOps, automation, and cloud-native technologies**. This bootcamp will be streamed **live on YouTube, Monday to Friday at 09:30 PM**, throughout Ramadan, making it accessible to professionals and learners worldwide.

Our goal is to provide hands-on, practical training on CI/CD, Kubernetes, Docker, GitLab, Monitoring, and End-to-End DevOps workflows. Each session is carefully structured so that each topic builds upon the previous one, ensuring a seamless learning experience.

By the end of this boot camp, you'll gain real-world skills in **automation, container orchestration, deployment pipelines, and monitoring**, empowering you to apply DevOps best practices in your projects and career.

**Subscribe for Live Bootcamp: [YouTube Channel](https://www.youtube.com/@babarzahoor)**

## 🏗️ Architecture

![DevOps Architecture](docs/images/architecture.txt)

This bootcamp implements a complete DevOps workflow with:
- Self-hosted GitLab for source control and CI/CD
- MicroK8s Kubernetes cluster for container orchestration
- Docker for containerization
- CheckMK for monitoring and observability
- Nginx for ingress and load balancing
- WordPress application deployment as a practical example

For a detailed architecture diagram and component descriptions, see the [Architecture Documentation](docs/architecture.md).

## 💻 Technologies Used

- **Containerization**: Docker
- **Container Orchestration**: Kubernetes (MicroK8s)
- **CI/CD**: GitLab
- **Monitoring**: CheckMK, Prometheus, Grafana
- **Web Server**: Nginx
- **Sample Application**: WordPress with MySQL
- **Operating System**: Ubuntu 22.04
- **Infrastructure as Code**: Terraform
- **Deployment Strategy**: Blue-Green Deployment

## 📝 Prerequisites

- Ubuntu 22.04 LTS (minimum)
- 4GB RAM, 2 CPU cores, 25GB storage (per node)
- Basic Linux command knowledge
- Understanding of networking concepts
- Git installed

## 📚 Installation Guides

Step-by-step installation guides are provided for all components:

- [Docker Installation on Ubuntu 22.04](Docker-Installation-Ubuntu-22.04.md)
- [MicroK8s Installation on Ubuntu 22.04](MicroK8s-Installation-ubuntun-22.04.md)
- [GitLab Self-Hosted Installation](Gitlab-Self-Hosted-Installation.md)
- [CheckMK Installation and Client Integration](CheckMK-Installation-and-Client-Integration-Ubuntu-22.04.md)
- [MicroK8s Integration with GitLab](MicroK8s-Integration-with-Gitlab.md)

For a quick start guide, see [Getting Started](docs/getting-started.md).

## 🚢 Deployments

Sample Kubernetes deployments included in this repository:

- [WordPress with MySQL](wordpress-deployment.yaml) - Complete application stack with persistent storage
- [Nginx Deployment](nginx-deployment.yaml) - Web server and ingress controller

Advanced deployment strategies:
- [Blue-Green Deployment Script](scripts/blue-green-deploy.sh) - Zero-downtime deployments
- [Security Scanning Script](scripts/security-scan.sh) - Container and manifest security scanning

## 📊 Monitoring

This bootcamp includes comprehensive monitoring setup with:

- **CheckMK**: Server health monitoring
- **Prometheus**: Metrics collection and storage
- **Grafana**: Visualization and dashboards

Monitoring configurations:
- [Prometheus Configuration](monitoring/prometheus-config.yaml)
- [Grafana Dashboard](monitoring/grafana-dashboard.json)

## 🔄 CI/CD Integration

Learn how to set up complete CI/CD pipelines with GitLab:
- Automated testing
- Container building
- Security scanning
- Deployment to Kubernetes
- Pipeline visualization

CI/CD configuration:
- [GitLab CI/CD Configuration](.gitlab-ci.yml)

## 🌐 Community

Join our growing community of DevOps enthusiasts:

- **Discord**: [Join our server](https://discord.gg/KJcKTTJp)
- **Facebook**: [Facebook Group](https://www.facebook.com/groups/learndevopswithbz)
- **LinkedIn**: [LinkedIn Group](https://www.linkedin.com/groups/14119593/)
- **WhatsApp**: [WhatsApp Group](https://chat.whatsapp.com/CywSgRC4GLWG8VZz96ej8E)
- **GitHub**: [DevOps-With-Babar-Zahoor](https://github.com/DevOps-With-Babar-Zahoor)

## 📺 Previous Bootcamps

- [OpenShift Bootcamp Ramadan 2024](https://www.youtube.com/playlist?list=PLBiQy5tO4R2MDO3rGieRcTd93QjYdc34b)
- [Kubernetes Bootcamp Ramadan 2023](https://www.youtube.com/playlist?list=PLBiQy5tO4R2OA3_eQ4wPXchN0XtODcP8z)
- [Linux Docker Kubernetes BootCamp 2022](https://www.youtube.com/playlist?list=PLBiQy5tO4R2N-W-1lvnNMVAJXqqSxujXQ)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

