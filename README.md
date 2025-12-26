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

```

<img width="1963" height="1127" alt="image" src="https://github.com/user-attachments/assets/933f0105-abbc-407b-a0bf-65445d19fbe8" />


---


🛠️ Technologies utilisées

- GitHub Actions (CI/CD)

- Python + Flask

- Docker

- CodeQL (SAST)

- Bandit (Sécurité Python)

- Trivy (Scan image Docker)

---

## ▶️ Pipeline GitHub Actions
<img width="2528" height="1242" alt="image" src="https://github.com/user-attachments/assets/f5b1a4e0-59c8-4405-9411-a058a6a10a52" />

---

## 🔍 Résultats CodeQL


<img width="2558" height="1113" alt="image" src="https://github.com/user-attachments/assets/77c42b4c-44aa-4cf6-a2f3-be1278d8604a" />

---

## ✅ Pipeline après correction

<img width="2548" height="1197" alt="image" src="https://github.com/user-attachments/assets/198ab727-1415-404f-ab94-be95597e7a34" />

---

# Dependency Security Pipeline

![DevSecOps](https://img.shields.io/badge/DevSecOps-Supply%20Chain%20Security-blue)
![CI/CD](https://img.shields.io/badge/GitHub-Actions-black)
![Security](https://img.shields.io/badge/Security-Automated-green)

---

## 📌 Objectif du projet

Ce projet implémente **DevSecOps**, qui consiste à sécuriser la **supply chain logicielle**
en analysant automatiquement les dépendances Python dans un pipeline CI/CD GitHub Actions.

---

## 🏗️ Architecture du projet

````
devsecops-lab/
├── .github/
│ └── workflows/
│ └── devsecops.yml
├── api/
│ └── app.py
├── Dockerfile
├── requirements.txt
└── README.md
````
<img width="641" height="721" alt="image" src="https://github.com/user-attachments/assets/15cd3d87-e251-4bc3-89d6-0422a9e2cb5b" />

---


### 🔹requirements.txt
<img width="2128" height="784" alt="image" src="https://github.com/user-attachments/assets/590d6bb8-8a4a-4d8f-958e-c5ef20fabe6f" />

---


### 🔹 Modifier le pipeline GitHub

<img width="2113" height="1220" alt="image" src="https://github.com/user-attachments/assets/27566f80-4ead-416e-a484-e83ca61b1519" />


### 🔹 Push
````
git pull --rebase origin main
git add .
git commit -m "Add dependency supply chain security"
git push origin main

````



---

## 📊 Résultats

- ✔ Sécurité Supply Chain activée
- ✔ Dépendances vérifiées avant le build Docker
- ✔ Blocage automatique des librairies vulnérables
- ✔ Pipeline DevSecOps complet

---

## 🎯 Conclusion

DevSecOps-2 permet d’empêcher l’intégration de dépendances vulnérables dès la phase CI/CD,
renforçant ainsi la sécurité globale de l’application.

---








