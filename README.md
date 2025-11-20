📘 CircleAI Platform
<p align="center"> <img src="/mnt/data/ChatGPT Image Nov 20, 2025, 11_02_58 AM.png" width="100%" /> </p> <h2 align="center">⚡ Enterprise Business Systems Suite</h2> <p align="center"><b>AI-powered HR & Legal management experience built for modern teams</b></p>
<div align="center"> <img src="https://img.shields.io/badge/Status-Active%20Development-blueviolet?style=for-the-badge" /> <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Django-5.0-0C4B33?style=for-the-badge&logo=django" /> <img src="https://img.shields.io/badge/Vue.js-3-42b883?style=for-the-badge&logo=vuedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white" /> </div>
🚀 Overview

CircleAI Platform is an enterprise-grade Multi-Tenant SaaS ecosystem combining:

🔹 CircleHR — Complete HR Management System
🔹 CircleLAW — Legal Office & Case Management System

Designed for scalability, security, and an exceptional modern UX.

✨ Key Features
🔷 CircleHR — Human Resources Suite

Employee records & profiles

Smart attendance tracking

Payroll & compensation engine

Performance reviews & KPIs

Requests & approval workflow

AI-powered insights

RBAC permissions model

🔷 CircleLAW — Legal Office Suite

Clients & case lifecycle

Court sessions & hearings

Secure document workspace

Real-time notifications

Audit trails & activity logs

Advanced search engine

🏗 Architecture
<p align="center"> <img src="https://via.placeholder.com/1000x450/111827/ffffff?text=Architecture+Diagram+(Coming+Soon)" /> </p>
Backend

Django 5

Django REST Framework

Celery workers

Redis

PostgreSQL

JWT Authentication

Multi-tenant isolation

Frontend

Vue 3

Vite

TailwindCSS

Axios API layer

Infrastructure

Docker + Docker Compose

Nginx reverse proxy

GitHub Actions CI

🖥 Tech Stack
Layer	Technologies
Backend	Django, DRF, Celery, Redis
Frontend	Vue, TailwindCSS, Vite
Database	PostgreSQL
Infrastructure	Docker, Nginx, GitHub Actions
Authentication	JWT, RBAC
Architecture	Multi-Tenant SaaS
🔐 Security & Compliance

RBAC permission system

Audit logging

Dependency vulnerability scanning (CI)

Secure authentication flows

Environment-scoped configs

Tenant-level data isolation

🧩 Development Workflow
Branch Strategy
main → production  
dev → active development  
feature/* → new features  
fix/* → bug fixes  

CI Pipeline

Linting

Security scanning

Docker image validation

Local Development
git clone https://github.com/CircleAI-django/circleai-platform.git
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
docker-compose up --build

🖼 UI Preview (Coming Soon)
<p align="center"> <img src="https://via.placeholder.com/700x380/4f46e5/ffffff?text=Dashboard+Preview" /> </p>
👥 Team
Name	Role
Ahmed Elmannan	Full-Stack Software Engineer
Abdullah Tahir	Full-Stack Software Engineer
📬 Contact

🌐 Website: https://elmannan.site

💼 LinkedIn: https://www.linkedin.com/in/ahmed-ata-elmannan-8a11a9238

📧 Email: a.elmannan@crclai.com

⭐ Project Status

🚧 Actively developed as part of the CircleAI organization.
