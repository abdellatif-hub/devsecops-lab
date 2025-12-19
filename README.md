# 🔐 DevSecOps Lab — CI/CD Security Pipeline

![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue)
![Security](https://img.shields.io/badge/Security-DevSecOps-red)
![Docker](https://img.shields.io/badge/Docker-Enabled-blue)

## 📌 Description
Ce projet est un **laboratoire DevSecOps** qui démontre l’intégration automatique de la sécurité dans un pipeline **CI/CD GitHub Actions** pour une API **Python Flask** conteneurisée avec Docker.

La sécurité est testée **à chaque push** grâce à des outils automatisés.

---

## 🧱 Architecture du projet
```bash
devsecops-lab/
├── api/
│   └── app.py
├── Dockerfile
└── .github/
    └── workflows/
        └── devsecops.yml
